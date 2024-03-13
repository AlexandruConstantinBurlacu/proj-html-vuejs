<script>
    export default {
        name: 'AppFooter',
    }
</script>

<template>
  <div class="footer">
    <div class="footerContainer">
      <div class="logo">
        <img src="../assets/images/author-logo-round-200x205.png" alt="Logo Avada">
      </div>

      <div class="aboutMe">
        <h4>about me</h4>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        </p>
      </div>

      <div class="usefulLinks">
        <h4>useful links</h4>
        <ul class="links">
          <li>> Latest Books</li>
          <li>> Upcoming Events</li>
          <li>> Recent Articles</li>
          <li>> Business Enquires</li>
          <li>> Visit My Foundation</li>
        </ul>
      </div>

      <div class="contactInfo">
        <h4>contact info</h4>
        <ul>
          <li>63 E. Studebaker Street</li>
          <li>Phone: (800) 000-0000</li>
          <li>Mobile: (800) 000-0000</li>
          <li>Email: info@your-company.com</li>
          <li></li>
        </ul>
      </div>
    </div>

    <div class="copyright">
      <p>
        Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress
      </p>
    </div>
    
  </div>
</template>

<style lang="scss">

  .footer * {
    color: white;
  }

  .footer {
    height: 400px;
    background-image: url("../assets/images/footer-3.jpg");
    background-size: cover;
    background-position: top;

    .footerContainer {

     padding-top: 79px;
     display: flex;
     flex-direction: row;
     justify-content: center;
     gap: 107px;


     h4 {
      text-transform: uppercase;
      margin-bottom: 34px;
     }

     li {
      list-style-type: none;
     }

      
      .logo img {
          width: 68px;
          height: auto;
          
      }
    
      .aboutMe p {
        max-width: 214px;
      }
    
    }

    .copyright p {
        text-align: center;
        margin-top: 54px;
        margin-bottom: 35px;
      }
  }
</style>