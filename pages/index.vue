<template>
  <div id="homediv">



        <div class = "mainchilddiv imageArea">
            <img id="myimage" src="~assets/vector.png" alt="myVectorArt">
        </div>

        <div class = "mainchilddiv textArea"> 
            <h1 class="title">Vighnesh S.</h1>
            <div class="subTitleDiv">


              <div class="subTitle">

                  <span>UI / UX Designer </span>

                </div>

                <div class="subTitleUnderline"></div>


            </div>
                
                

                <div class="subTitleDiv">


              <div class="subTitle">

                  <span>ML Enthusiast </span>

                </div>

                <div class="subTitleUnderline"></div>


            </div
            
            
            
            
            ><div class="subTitleDiv">


              <div class="subTitle">

                  <span>Full Stack Developer</span>

                </div>

                <div class="subTitleUnderline"></div>


            </div>



            <div class="subTitleDiv">


              <div class="subTitle socialSubtitle">

                  <a href="https://twitter.com/_vighnesh_s_" class="social" target="_blank">
                  
                  <font-awesome-icon :icon="['fab', 'twitter']"/>
                  
                  </a>

                  <a href="https://www.linkedin.com/in/vighnesh-s-688044165/" class="social" target="_blank">
                  
                  <font-awesome-icon :icon="['fab', 'linkedin']"/>
                  
                  </a>


                  <a href="http://github.com/aka8921" class="social" target="_blank">
                  
                  <font-awesome-icon :icon="['fab', 'github']"/>

                  </a>
                  
                  
                  

                </div>

                


            </div>
                
                <!-- <span>
                    <i class="fab fa-linkedin"></i>
                    <i class="fab fa-github-square"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-facebook-square"></i>
                    <i class="fab fa-telegram"></i>
                    <i class="fab fa-youtube-square"></i>
                </span> -->
            
        </div>
    </div>

</template>

<script>

export default {
  components: {
    
  },
  head () {
    return {
      title: "Vighnesh | Home",
    }
  }
}
</script>

<style>

a{
  text-decoration: none;
  color: #fff;
}

/* verified */


/* Main div */

#homediv{
    height: 100vh;
    width: 100%;
    background-color: #ff8800;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    z-index: 1;
    flex-wrap: wrap;
}




/* Image */

#myimage{
    height: 50vw;
    max-height:80vh;
    /* background-color: aqua; */
    
}


/* Home Div Children */


.mainchilddiv{
    flex:1;
    text-align: center;
    /* background-color: red; */
    
}

.imageArea{
    display: flex;
    justify-content: center;
    align-items: flex-end;
}





/* Right Side Text Area */


.textArea{
    display: flex;
    flex-direction: column;
    align-items: baseline;
    /* background-color: blue; */
}


.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 900;
  font-size: 8vw;
  color: #ffffff;
  letter-spacing: 1px;
  /* background-color: chocolate; */
  justify-self: baseline;
}

.subTitleDiv{
display: flex;
width: 100%;
/* background-color: aqua; */
}

.subTitle{
    /* text-decoration: none;
    list-style-type: none;
    margin: 0;
    padding: 0; */
    color: #ffffff;
    font-weight: 900;
    font-size:1.8em;
    margin: 0;
    padding: 0;
    /* background-color: blue; */
    
    
}

.subTitleUnderline{
  background-color: #fff;
  height: 3px;
  align-self: flex-end;
  margin-bottom: 0.4em;
  width: auto;
  margin-left: 1em;
  flex:1;
}

/* Social Media Links */

.social{
  margin-right: .5em;
}







@media screen and (max-width: 1000px) {
  #myimage{
    height: 35vh;
  }

  #homediv{
    flex-direction: column;
  }
  .title{
    font-size: 12vw;
  }

  .subTitle{
    font-weight: 100;
    font-size: 4vw;
  }

  .homediv{
    padding:1em;
  }

  .socialSubtitle{
    margin-top:2vh;
  }

}


</style>