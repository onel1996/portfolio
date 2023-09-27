<template>
<div class="main-container">
    <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
        <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
        <img src="../assets/MP.png" alt="">
        <p>{{ projectData.ProjectsArray[index].About }}</p>
    </div>
</div>

</template>


<script>
import jsonData from "/projects.json"
export default {
    data(){
        return{
            projectData: jsonData
        }
    }
}
</script>

<style>

    .main-container{
        margin-top: 5%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
    }
    .project-card{
        margin: 10px;
        flex-wrap: 0 0 40px;
        background-color: #fff;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 24) 0 3px 8px;
    }
    .project-card img{
        height: 10rem;
    }
</style>