<template>
<div>
<div class="container-sm container-style">
    <Heading headingValue="Skills & Achievements"/>
    <div class="alert alert-info" role="alert">
        <div class="row">
            <div class="col-sm-1">
                <img src="../assets/images/vue.png" class="icon-image-style" alt="Vue Js" title="Vue Js">  
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/aws.png" style="margin-top: 15%;" class="icon-image-style" alt="AWS" title="Amazon Web Services">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/graphql.png" class="icon-image-style" alt="GraphQL" title="GraphQL">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/quasar.png" class="icon-image-style" alt="Quasar Framework" title="Quasar Framework">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/storybook.png" class="icon-image-style" alt="Story Book" title="Story Book">
            </div> 
            <div class="col-sm-1">
                <img src="../assets/images/spring.png" class="icon-image-style" alt="Spring" title="Spring">
            </div> 
            <div class="col-sm-1">
                <img src="../assets/images/angular.png" class="icon-image-style" alt="Angular" title="Angular">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/Limeroad/bootstrap.png" class="icon-image-style" alt="Boot Strap" title="Bootstrap">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/Limeroad/javascript.png" class="icon-image-style" alt="Java Script" title="Javascript">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/azure.png" class="icon-image-style" alt="Microsoft Azure" title="Microsoft Azure">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/html.png" class="icon-image-style" alt="HTML 5" title="HTML 5">
            </div>
            <div class="col-sm-1">
                <img src="../assets/images/css.png" class="icon-image-style" alt="CSS3" title="CSS 3">
            </div>
        </div>
    </div>
    <div class="alert alert-success" role="alert">
        <span class="achievement-style">Insta Rise Award </span>- For Showing great flexibility and adaptability towards learning new technology.<span><button class="btn btn-success btn-style" data-toggle="modal" data-target="#InstaRise">View</button></span>
    </div>

    <div class="alert alert-success" role="alert">
        <span class="achievement-style">Client Recognition</span>- For Being Instrumental to Core UI Development and delivering complex features on time.<br><span class="note-design">** Due to company's policy cannot disclose those letters</span>
    </div>

</div>
    <div class="modal fade u--flipY" id="InstaRise" data-backdrop="static" data-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
        <div class="modal-dialog modal-dialog-scrollable">
            <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="staticBackdropLabel">Insta Rise Award</h5>
            </div>
            <div class="modal-body">
                <img src="../assets/images/documents/instaRise.png" width=110% alt="Award Image">
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            </div>
            </div>
        </div>
    </div>
</div>
</template>
<script>
import Heading from './Heading.vue';
export default {
    nama: "SkillsAndAchievement",
    components:{
        Heading
    }
}
</script>
<style scoped>
.container-style{
    margin-bottom: 5%;
}
.icon-image-style{
    width: 100%;
    padding: 1%;
    opacity: 1;
}
.skill-design{
    background-color: white;
    padding: 1%;
    margin: 1%;
}
.achievement-style{
    color: Red;
    font-weight: bold;
}
.btn-style{
    margin-left: 5%;
}
.note-design{
    color: red;
    font-size: x-small;
    text-align: left;
}
</style>