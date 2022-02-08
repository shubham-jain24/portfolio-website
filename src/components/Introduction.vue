<template>
<div class="container-sm u--slideRight">
    <div class="intro-style">
        <h1>Hi, My name is </h1><h1><span class="name-style"> Shubham Jain </span></h1>
        <h3>I am a Specialist Programmer <span class="mid-style">(Power Programmer) at Infosys</span></h3>
        <h3>I <span class="mid-style">enjoy</span> working on both <span class="mid-style">Frontend and Backend </span> part of Applications.</h3>
        <div>
            <a href="https://www.linkedin.com/in/shubham-jain-948240164/"><img src="../assets/images/Intro/linkedin.png" class="icon-image-style" alt="LinkedIn"></a>
            <a href="https://github.com/shubham-jain24"><img src="../assets/images/Intro/github.png" class="icon-image-style" alt="Git Hub"></a>
        </div>

        <div>
            <a href="#Contact"><button class="btn btn-style"> Ping Me Here </button></a>
        </div>
    
    </div>
</div>
</template>
<script>
export default {
    name: "Introduction",
}
</script>
<style scoped>
.container-style{
    margin-top: 10%;
    margin-bottom: 10%;
}
.name-style{
    color: rgb(83, 238, 252);
    font-size: 150%;
}
.intro-style{
    color: white;
    padding: 2%;
    text-align: left;
    line-height: 2%;
    margin-top: 7%;
    margin-bottom: 7%;
}
.mid-style{
    color: rgb(83, 238, 252);
}
.icon-image-style{
    margin-top: 2%;
    width: 5%;
    margin-right: 2%;
}
.btn-style{
    background-color: rgb(83, 238, 252);
    color: black;
    margin-top: 2%;
    padding: 1%;
    font-weight: bold;
}
</style>