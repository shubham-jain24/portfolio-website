<template>
    <div>
        <div class="container-sm">
                <Heading headingValue="Projects"/>

                <div class="row row-style justify-content-center">
                    <div class="col-sm-3 heading-style"> 
                        <h1> Dream Book</h1>
                        <h6> An Application Created for people to post and view the content related to their interest. No more need to scrool down pages in order to find relevant post.</h6>
                        <img src="../assets/images/logo.png" width=20% class="icon-image-style" alt="Boot Strap">
                    </div>
                    <div class="col-sm-6 content-style justify-content-center">
                        <p> > Created the application Using MEAN Stack. </p>
                        <p> > Backend created using node js and database maintained in MongoDB(NoSQL).</p>
                        <p> > Frontend created using Angular js. </p>
                        <p> > Backend hosted using Heroku.</p>
                        <p> > Frontend hosted on Google Firebase.</p>
                    </div>
                    <div class="col-sm-2 btn-body-style justify-content-center">
                        <div>
                            <a href="https://github.com/shubham-jain24/Social-Networking-Site"><button class="btn btn-dark btn-design">View Code</button></a>
                        </div>
                        <div>
                            <a href="https://dream-book-application.web.app/"><button class="btn btn-dark btn-design">View Project</button></a>
                        </div>
                    </div>

                </div>

                <div class="row row-style justify-content-center">
                    <div class="col-sm-2 btn-body-style justify-content-center">
                        <a href="https://github.com/shubham-jain24/J-Tracker-Application-Frontend/tree/master">
                        <div>
                            <button class="btn btn-dark btn-design">View Frontend Code</button>
                        </div>
                        </a>
                        <a href="https://github.com/shubham-jain24/J-Tracker-Application-Backend">
                        <div>
                            <button class="btn btn-dark btn-design">View Backend Code</button>
                        </div>
                        </a>
                        <div>
                            <a href="https://drive.google.com/drive/folders/1yDBwxzgssF-_RWsNsR-3QXK-O-09rkrm?usp=sharing"><button class="btn btn-dark btn-design">View Project Video</button></a>
                        </div>
                    </div>
                    <div class="col-sm-6 content-style justify-content-center">
                        <p> > Application is built using Spring MVC.</p>
                        <p> > GraphQL is used to fetch data from MongoDB.</p>
                        <p> > Frontend of the application is built using Vue js. </p>
                        <p> > Apollo client is used at frontend layer to fetch data through graphql quries.</p>
                    </div>
                    <div class="col-sm-3 heading-style"> 
                        <h1>JTicket Tracker</h1>
                        <h6>An Application which allow user to create a Ticket(Epic and Bugs) and create user story associated to the ticket created. An additional feature of adding commentis also added to give more comprehensive view.</h6>
                    </div>
                </div>

                

                <div class="row row-style justify-content-center">
                    <div class="col-sm-3 heading-style"> 
                        <h1>Advanced Vehicle Parking System</h1>
                        <h6>An Application created to automate the whole parking system. Insted of using IOT used image processing to find out the empty parking space in the parking lot.</h6>
                    </div>
                    <div class="col-sm-6 content-style justify-content-center">
                        <p> > OCR (Optical Character Recognition) is used to read the vehical number plate.</p>
                        <p> > YOLO (You Only Look Once) algorithm is used to find out the available parking spaces.</p>
                        <p> > Contribution - Prepared the user interface which allow user to book the parking space in prior. </p>
                        <p> > Interface provides realtime data to user about the parking space.</p>
                        <p> > Additional Contribution - Done analysis to find out the correct machine learning algorithm to be used in the project.</p>
                    </div>
                    <div class="col-sm-2 btn-body-style justify-content-center">
                        Group Project - 
                        Project Report Submitted to University as major project report.
                    </div>
                    
                </div>

        </div>
    </div>
</template>
<script>
import Heading from './Heading.vue';
export default {
    name: "Projects",
    components:{
        Heading
    }
}
</script>
<style>
.content-style{
    color: rgb(83, 238, 252);
    background-color: black;
    padding: 2%;
    margin: 1%;
    text-align: left;
    
}
.btn-body-style{
    background-color: rgb(83, 238, 252);
    padding: 2%;
    margin: 1%;
    border-style: double;
    border-color: black;
    color: black;
}
.heading-style{
    background-color: white;
    padding: 2%;
    margin: 1%;
    border-style: double;
    border-color: black;
}
.btn-design{
    background-color: black;
    color: white;
    padding: 2%;
    margin: 3%;
}
</style>