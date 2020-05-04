<template>
  <div class="main">
    
      <div class="text-center notification fixed-top ">
        <div class="row">
        <div class="col-md-12 text-center   " id="navbar">
        <p class="d-inline-block">
          By accessing and using this website, you acknowledge that you have read and
          <br />understand our Cookie Policy, Privacy Policy, and our Terms of Service.
        </p>
        <button class="btn btn-primary ml-4" style="margin-top:-20px"> Got It</button>
      </div>
        </div>
    </div>

    <div class="jumbotron" id="jumbotron">
      <img src="../assets/logo-white.png" id="gambar" class="mb-5" />
      <div class="col-md-12 styleText">
        <h2 class="text-center">Hello! I'm Luiz Adam</h2>
        <h3 class="text-center">Consult, Design, and Develop Websites</h3>
        <p class="text-center">
          Have something great in mind? Feel free to contact me.
          <br />I'll help you to make it happen.
        </p>
        <button class="btn btn-outline-primary btnContact">Let's Make Contact</button>
      </div>
    </div>
    <div class="container-fluid">
      <div class="text-center">
        <h4>How Can I Help You?</h4>
        <p>
          Our work then targeted, best practices outcomes social innovation synergy.
          <br />Venture philanthropy, revolutionary inclusive policymaker relief. User-centered
          <br />program areas scale.
        </p>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2">Consult</h4> 
            <i class="far fa-comment fa-2x mt-2 mr-2"></i>
            </div>
            
            <div class="card-body">
              <p>
                Co-create, design thinking; strengthen infrastructure resist granular.
                Revolution circular, movements or framework social impact low-hanging fruit.
                Save the world compelling revolutionary progress.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2">Design</h4> 
            <i class="fas fa-paint-brush fa-2x mt-2 mr-2"></i>
            </div>
            <div class="card-body">
              <p>
                Policymaker collaborates collective impact humanitarian shared value
                vocabulary inspire issue outcomes agile. Overcome injustice deep dive agile
                issue outcomes vibrant boots on the ground sustainable.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          
          <div class="card">
             <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2">Develop</h4> 
            <i class="fas fa-cubes fa-2x mt-2 mr-2"></i>
            </div>
            
            <div class="card-body">
              <p>
                Revolutionary circular, movements a or impact framework social impact low-
                hanging. Save the compelling revolutionary inspire progress. Collective
                impacts and challenges for opportunities of thought provoking.
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-md-4">
          <div class="card">
             <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2 " >Marketing</h4> 
            <i class="fas fa-bullhorn fa-2x mt-2 mr-2 "></i>
            </div>
            <div class="card-body">
              <p>
                Peaceful; vibrant paradigm, collaborative cities. Shared vocabulary agile,
                replicable, effective altruism youth. Mobilize commitment to overcome
                injustice resilient, uplift social transparent effective.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2" style="display:inline-block">Manage</h4>
              <i class="fas fa-tasks text-right fa-2x mt-2 mr-2"></i>
            
            </div>
            
            <div class="card-body">
              <p>
                Change-makers innovation or shared unit of analysis. Overcome injustice
                outcomes strategize vibrant boots on the ground sustainable. Optimism,
                effective altruism invest optimism corporate social.e.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
             <div class="d-flex justify-content-between">
              <h4 class="judul ml-3 mt-2">Evolve</h4>
            <i class="fas fa-chart-line fa-2x mt-2 mr-2"></i>
            </div>
            <div class="card-body">
              <p>
                Activate catalyze and impact contextualize humanitarian. Unit of analysis
                overcome injustice storytelling altruism. Thought leadership mass
                incarceration. Outcomes big data, fairness, social game-changer.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="card " id="alertSide">
      <div class="card-body">
        <button class="btn btn-default" style="float:right;color:white" onclick="this.parentElement.style.display='none';">&times;</button> 
        <h4 class="mt-4" style="color:white">Get latest updates in web technologies</h4>
        <p style="color:white">
          I write articles related to web technologies, such as design trends, development
          <br />tools, UI/UX case studies and reviews, and more. Sign up to my newsletter to get
          <br />them all.
        </p>
         <input type="text" class="form" placeholder="Email address" > <button class="btn btn-warning btnAlert" style="color:white">Count Me In!</button>
      </div>
    </div>
    </div>
    <div class="inifooter mt-5" style="height:50px;width100%;background:#050328">
      <p
        class="text-center"
        id="footer"
        style="color:#546db3"
      >© 2020 Luiz Adam. All rights reserved.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  }
};
</script>
<style scoped>
.main {
  margin: 0;
  padding: 0;
  background-color: #e5e5e5;
}
.jumbotron {
  background-image: url(../assets/bg.jpg);
  position: relative;
  display: block;
  width: 100%;
  height: 500px;
}

.jumbotron::before{
  background-color:#002B62;
  content: '';
  opacity: 0.8;
  position: absolute;
  margin:0;
  top:0;
  left:0;
  width: 100%;
  height: 500px;
}

.notification {
  background-color: #e5e5e5;
}
.btnNotif {
  display: inline;
}

.styleText {
  color: white;
  float: center;
}

.btnContact {
  border-color: white;
  color: white;
  margin-left: 44%;
}
#gambar {
  width: 40px;
  height: 40px;
  position: relative;
}
.card {
  margin-top: 2rem;
  background-color: #e5e5e5;
  -webkit-box-shadow: 0px 0px 6px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 6px 0px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 6px 0px rgba(0, 0, 0, 0.75);
}
.btnContact:hover {
  background-color: white;
  color: #016496;
}

#alertSide {
  position: absolute;
  margin-top: -130px;
  margin-left:-10px;
  opacity: 0.9;
  background-color: #1682c3;
}
.form{
  width:70%;
}

@media only screen and (max-width: 600px) {
  #gambar {
    width: 40px;
    height: 40px;
    margin-top: 100px;
  }
  .jumbotron {
  background-color:#016496;
  background-image: url(../assets/bg.jpg);
  width: 100%;
  height: 600px;
}
.jumbotron::before{
  background-color:#002B62;
  content: '';
  opacity: 0.8;
  position: absolute;
  margin:0;
  top:0;
  left:0;
  width: 100%;
  height: 600px;
}
  .btnContact {
    border-color: white;
    color: white;
    margin-left: 25%;
  }
  #alertSide {
  position: absolute;
  margin-top: -290px;
  opacity: 0.9;
  width: 98%;
}
.form{
  width:100%;
  margin-bottom:7px
}
.btnAlert{
  width: 100%;
}
}
</style>
