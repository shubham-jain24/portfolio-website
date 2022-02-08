<template>
<div class="u--slideDown">
    <nav :class="projectStyle" >
        <div class="container-fluid">
    <a class="navbar-brand" @click = "update_active_link_style('Home')" href="#">
    <img src="../assets/images/AppLogo.png" alt="" width="60" height="45" class="d-inline-block align-text-top">
    
    </a>
    <button class="navbar-toggler"  type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a :class="activeStyleHome" @click = "update_active_link_style('Home')" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a :class="activeStyleFindJob" href="#Skill">Skills & Achievements</a>
        </li>
        <li class="nav-item">
          <a :class="activeStyleRecruit" href="#WorkExperience">Work Experience</a>
        </li>
        <li class="nav-item">
          <a :class="activeStyleRecruit" href="#Projects">Projects</a>
        </li>
        <li class="nav-item">
          <a :class="activeStyleContact" href="#Contact">Ping Here</a>
        </li>
      </ul>
    </div>
  </div>
    </nav>
</div>
</template>
<script>
export default {
  name: 'PageHeader',
  props: {
    msg: String

  },
  data(){
      return{
          projectStyle: "navbar navbar-expand-lg navbar-light  header-body",
          activeStyleHome: "nav-link active",
          activeStyleFindJob: "nav-link",
          activeStyleRecruit: "nav-link",
          activeStyleContact: "nav-link",
      }
  },
  methods:{
      update_active_link_style(link_name){
          if( link_name == 'Recruit'){
            this.activeStyleHome = "nav-link"
            this.activeStyleFindJob = "nav-link"
            this.activeStyleRecruit = "nav-link active"
            this.activeStyleContact = "nav-link"
          }
          else if ( link_name == 'FindJob'){
            this.activeStyleHome = "nav-link"
            this.activeStyleFindJob = "nav-link active"
            this.activeStyleRecruit = "nav-link"
            this.activeStyleContact = "nav-link"
          }
          else if ( link_name == 'Contact'){
            this.activeStyleHome = "nav-link"
            this.activeStyleFindJob = "nav-link"
            this.activeStyleRecruit = "nav-link"
            this.activeStyleContact = "nav-link active"
          }
          else{
            this.activeStyleHome = "nav-link active"
            this.activeStyleFindJob = "nav-link"
            this.activeStyleRecruit = "nav-link"
            this.activeStyleContact = "nav-link"
          }
          this.$emit('update-page', link_name);

      }
  }
}
</script>
<style>
.header-body{
  background-color: rgb(83, 238, 252);
  color: black;
  font-weight: bold;
}
.style-heading{
  padding: 1%;
  margin-top: 50%;
}
</style>