<template id="app">
    <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background}">
        <title>Paul Even</title>
        <Navbar_ />
        <v-container fluid>
            <v-row>
                <v-col cols="4">
                    <v-img src="@/assets/vivatech_pic.jpg" contain max-height="500"></v-img>
                </v-col>
                <v-col cols="5">
                    <h4 class="pt2 top">Hello, I'm Paul.</h4>
                    <h1 class="white--text">Engineering Student</h1>
                    <p class="grey--text">I am an undergraduate Master of Science student and Creative Technologist at the<br /> De Vinci Innovation Center.
                         I'm a part of the Human Learning group, where I can develop my knowledge on humans and their interactions with their surroundings.
                         Passionnate about human senses and art, I always look to create experiences to play with people's sensations.
                         I have been studying the effects of smells, lights and sounds in the purpose to create immersive art.
                    </p>
                    
                </v-col>
                <v-col cols="12" class="padd">
                    <div class="first" id="about">
                        <v-row>
                            <v-col cols="12">
                                <div class="child bgColor1">
                                    <v-icon color="#5F2369" x-large class="ml-3">
                                        mdi-heart-pulse
                                    </v-icon>
                                    <h3 class="white--text ml-3 mt-4">Bio-medical Sensors</h3>
                                    <p class="grey--text ml-3 mt-6">Using medical sensors and computing the data to create interactive technologies.
                                    </p>
                                    
                                </div>
                                <div class="child bgColor2">
                                    <v-icon color="#FFFFFF" x-large class="ml-3">mdi-palette</v-icon>
                                    <h3 class="white--text ml-3 mt-4">Art Installations</h3>
                                    <p class="grey--text ml-3 mt-6">
                                        Developping innovative<br/>installations that combine<br/>immersion and interactivity.
                                    </p>
                                    
                                </div>
                                <div class="child bgColor1">
                                    <v-icon color="#5F2369" x-large class="ml-3">mdi-brain</v-icon>
                                    <h3 class="white--text ml-3 mt-4">Neurology</h3>
                                    <p class="grey--text ml-3 mt-6">
                                        Understanding the effects<br /> of our different senses<br /> and our brain's responses.
                                    </p>
                                    
                                </div>
                            </v-col>
                            <v-col cols="12">
                                <div class="child bgColor1">
                                    <v-icon color="#5F2369" x-large class="ml-3">
                                        mdi-palette-swatch
                                    </v-icon>
                                    <h3 class="white--text ml-3 mt-4">UX/UI Design</h3>
                                    <p class="grey--text ml-3 mt-6">Development of phone<br/>applications, websites<br/>and other softwares.
                                    </p>
                                    
                                </div>
                                <div class="child bgColor2">
                                    <v-icon color="#FFFFFF" x-large class="ml-3">mdi-memory</v-icon>
                                    <h3 class="white--text ml-3 mt-4">Electronic Design</h3>
                                    <p class="grey--text ml-3 mt-6">
                                        Components networking, <br/>printed circuit board design <br/>and textile integration.
                                    </p>
                                    
                                </div>
                                <div class="child bgColor1">
                                    <v-icon color="#5F2369" x-large class="ml-3">mdi-database</v-icon>
                                    <h3 class="white--text ml-3 mt-4">Database Administration</h3>
                                    <p class="grey--text ml-3 mt-6">
                                        Design, deployment and administation of databases for real-time communication.
                                    </p>
                                    
                                </div>
                            </v-col>
                            <v-col cols="12" class="mt-10">
                                <div class="child1">
                                    <h1 class="pt mt-4 number">10+</h1>
                                    <h3 class="white--text mt-4">Completed projects</h3>
                                </div>
                                <div class="child2 mRight">
                                    <v-row>
                                        <v-col cols="12" class="childcol">
                                            <div class="child2 mButton padding bgColor1">
                                                <h1 class="pt">5</h1>
                                                <p class="grey--text">Years of University</p>
                                            </div>
                                        </v-col>
                                        <v-col cols="12" class="childcol">
                                            <div class="child2 padding bgColor1">
                                                <h1 class="pt">3</h1>
                                                <p class="grey--text">Companies</p>
                                            </div>
                                        </v-col>
                                    </v-row>
                                </div>
                                <div class="child2">
                                    <v-row>
                                        <v-col cols="12" class="childcol">
                                            <div class="child2 mButton padding bgColor1">
                                                <h1 class="pt">3</h1>
                                                <p class="grey--text">Countries</p>
                                            </div>
                                        </v-col>
                                        <v-col cols="12" class="childcol">
                                            <div class="child2 padding bgColor1">
                                                <h1 class="pt">9</h1>
                                                <p class="grey--text">Programming Languages</p>
                                            </div>
                                        </v-col>
                                    </v-row>
                                </div>
                            </v-col>
                        </v-row>
                    </div>
                    
                </v-col>
                
                <v-col md="4" offset-md="2" class="projects" id="project">
                    <h4 class="pt">RECENT PROJECTS</h4>
                    <p class="grey--text"> Art, relaxation, physiological signal analysis and more...</p>
                </v-col>
                <v-col md="3" class="text-end">
                </v-col>
                <v-col md="3" offset-md="2">
                        <v-img src="@/assets/foreign_nature.jpg" max-height="250px" contain></v-img>
                </v-col>
                <v-col md="2">

                </v-col>
                <v-col md="3">
                    
                        <v-img src="@/assets/sth_shirt.jpeg" max-height="250px" contain></v-img>
                    
                </v-col>
                <v-col md="3" offset-md="2">
                    <v-btn color="white" dark text class="ml-n4">
                        Art of Life (work in progress)
                    </v-btn><br />
                    
                </v-col>
                <v-col md="2">

                </v-col>
                <v-col md="3">
                    <v-btn color="white" dark text class="ml-n4">
                        HeRa Shirt -&nbsp;<a href="https://smart-textiles-hub.com/" target="_blank" class="purple--text">Smart Textiles Hub</a>
                    </v-btn><br />
                    
                </v-col>

                <v-row>
                <v-col md="3" offset-md="2">
                    
            <v-row>
                    <p class="grey--text"> This project aims to generate <u>immersive art</u> from <u>human biometric data</u>.
                        Recovered data from multiple sensors (<u>Electrocardiogram, Electrodermal Skin Activity, Body Temperature...</u>)
                        will be used to generate <u>music and visuals</u> in the purpose to create a <u>personnal and 
                        exceptionnal experience</u> for every user.

                        
                        <br />
                        
                    </p>

                    
            </v-row>
                    
                    
                    
                
            </v-col>
            <v-col md="2">

            </v-col>
            <v-col md="3">
                <v-row>
                    <p class="grey--text">
                        This <u>wearable technology</u> aims to help companies <u>monitor</u> their employees' 
                        <u>vital signs</u> to <u>react faster in case of an emergency</u>. The T-Shirt is equipped with 
                        integrated sensors that can recover <u>Electrocardiogram (ECG) and GPS position</u> data, which is 
                        transmitted to a <u>phone application</u> that is specifically designed to work with the T-Shirt. 
                        The phone application enables the user to <u>view their information</u> and the <u>data collected
                         from their fellow team members</u>. The design and development of the T-shirt and the associated 
                         phone application were carried out with a focus on creating a seamless user experience, 
                         ensuring the collected data's ease of use and accuracy.
                        
                        
                    </p>

                    
            </v-row>
            </v-col>
        </v-row>



                <v-col md="3" offset-md="2">
                    
                        <v-img src="@/assets/smellful.png" contain></v-img>
                    
                </v-col>
                <v-col md="2">

                </v-col>
                <v-col md="3">
                    
                        <v-img src="@/assets/stressbud.png" contain></v-img>
                    
                </v-col>
                <v-col md="3" offset-md="2">
                    
                        <v-btn color="white" dark text class="ml-n4">
                        Smellful
                    </v-btn>
                    
                      
                </v-col>
                <v-col md="2">

                </v-col>
                <v-col md="3">
                    <v-btn color="white" dark text class="ml-n4">
                        Stressbud
                    </v-btn><br />
                                      
                </v-col>
                
                <v-row>
                <v-col md="3" offset-md="2">
                    
            <v-row>
                    <p class="grey--text"><u>Increasing demands</u> at the workplace and in school is a major source 
                        of <u>stress</u> for people in the developed world. Due to the difficulty switching contexts, 
                        this stress not only affects people during working hours but also at home during time off. 
                        Given the benefits of <u>aromatherapy</u> for enhancing concentration and relaxation, 
                        Smellful examines how the sense of smell can be used to help people switch between 
                        working and relaxing contexts. <br />
                        Using an olfctory interface that releases dry smells and a phone application, Smellful 
                        allows the users to choose when an which smell they want to relase, helping them in
                        different way, including <u>relaxing</u> them, giving them a <u>boost of energy</u> or increasing <u>concentration</u>.
                        
                        <br />
                        <a href="https://dvic.devinci.fr/projects/smellful" target="_blank">
                        <v-btn  color="#5F2369" dark text class="ml-n4">
                        Know more
                        <v-icon right>mdi-arrow-right</v-icon>
                        
                    </v-btn>
                </a>
                    </p>

                    
            </v-row>
                    
                    
                    
                
            </v-col>
            <v-col md="2">

            </v-col>
            <v-col md="3">
                <v-row>
                    <p class="grey--text">
                        StressBud is a <u>wooden fidget-toy</u>, that will help <u>increase your 
                        focus</u>, while also <u>reducing your stress</u>. It is small, discreet and silent. 
                        All you need to fidget while making everyone staying focused !<br/> 
                        How do I use it ? That is where you can get creative. 
                        We have designed it for you to place your thumb on the screw and move it, 
                        but you can play with it in anyway you can imagine.
                        How does it work ? Studies have shown that fidgeting can help improve focus and reduce stress
                        levels by stimulating different parts of the brain, including those responsible for 
                        attention and focus.
                        
                        <a href="https://www.kickstarter.com/projects/stressbud/quickstarter-stressbud-a-fidget-toy-to-focus" target="_blank">
                        <br />
                        <v-btn  color="#5F2369" dark text class="ml-n4">
                        Know more
                        <v-icon right>mdi-arrow-right</v-icon>
                        
                    </v-btn>
                </a>
                    </p>

                    
            </v-row>
            </v-col>
        </v-row>

                
                        <div class="second">
                            <div class="secondchild" id="contact">
                            <v-row>
                                <v-col cols="7">
                                    <h1 class="white--text">
                                        Let's work together on<br />your next project !
                                    </h1>
                                    <p class="grey--text">
                                        Here are my LinkedIn and Gmail links.
                                    </p>
                                </v-col>
                                <v-col cols="5">
                                    <br />
                                    <br />
                <v-row>
                
                <v-col cols="12" sm="12">
                    <v-card-text class="pt-2">
                        <v-btn  class="mx-1 white--text" icon>
                            <a href="https://www.linkedin.com/in/paul-even/">
                            <v-icon 
                            x-large class="ml-3" color="#FFFFFF">
                                        mdi-linkedin
                                    </v-icon>
                                </a>

                                
                        
                    </v-btn>

                    <v-btn  class="mx-1 white--text" icon>
                            <a href="https://mail.google.com/mail/?view=cm&fs=1&to=pauleven95@gmail.com">
                            <v-icon 
                            x-large class="ml-3" color="#FFFFFF">
                                        mdi-gmail
                                    </v-icon>
                                </a>

                                
                        
                    </v-btn>
                    </v-card-text>
                </v-col>
                
            </v-row>
                                </v-col>
                            </v-row>
                        </div>
                        </div>
                        <v-toolbar class="topTolbar" color="#111111" dark flat>
                            <div style="position: absolute; margin-left: auto; margin-right: auto; left: 0; right: 0; text-align: center;">
                            </div>
                        </v-toolbar>                     
                    
            </v-row>
        </v-container>
        
    </v-app>
    
</template>

<script>
import Navbar_ from '@/components/Navbar'







export default {
    name: 'Home_',

    components: {
        Navbar_,
        
        
       
    },
    
    
}


</script>

<style scoped>

.top{
    margin-top: 180px;
}

.topInverse{
    margin-top: -250px;
}

.topTolbar{
    margin-top: 100px;
    text-align: center;
}

.first{
    width: 100%;
    height: 610px;
    background: linear-gradient(
        to right,
        #181818,
        #181818 50%,
        #111111 50%,
        #111111
    );
    text-align: center;
    padding: 2rem 2rem;
}

.second{
    width: 100%;
    height: 200px;
    background: #181818;
    text-align: center;
    padding: 2rem 2rem;    
}

.secondchild{
    width: 50%;
    display: inline-block;
    background-color: #1e1e1e;
    padding: 2rem 1rem;
    vertical-align: middle;
    text-align: left;
    margin-top: 20px;
    
}

.child{
    display: inline-block;
    padding: 2rem 1rem;
    vertical-align: middle;
    text-align: left;
    margin-right: 8px;
    width: 275px;
    height: 275px;
    text-align: center;
}

.bgColor1{
    background-color: #1e1e1e;
}

.bgColor2{
    background-color: #5F2369;
}

.child1{
    display: inline-block;
    padding: 2rem 1rem;
    vertical-align: middle;
    margin-right: 5px;
    width: 240px;
}

.child2{
    display: inline-block;
    width: 245px;
    vertical-align: middle;
}

.mRight{
    margin-right: 8px;
}

.mButton{
    margin-bottom: 8px;
}

.padding{
    padding: 8px 0px;
}

.col-12.padd{
    padding: 12px 0 !important;
}

.col-12.childcol{
    padding: 0 !important;
}

h1.number{
    font-size: 50px;
    font-weight: bold;
}

.pt{
    color: #5F2369;
}

.pt2{
    color: #782C84;
}

.butto{
    color: #FFFFFF
}
.sth{
    color: "#5F2369"
}

.projects{
    padding-top: 300px;
}


a:link {
  color: "#5F2369";
  background-color: transparent;
  
}
a:visited {
  color: "#5F2369";
  background-color: transparent;
}
a:active {
  color: "#5F2369";
  background-color: transparent;
}
</style>