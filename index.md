---
title: Lea Gregorka
permalink: /
breadcrumb: Home
featuredimage: /
---

<!-- Styles only applied in main page -->
<style>
.content-image {
  display: none;
}
.content {
  width: 100%;
  padding: 0;
}
.content-margin {
  padding: 0;
}
</style>
<!-- Styles only applied in main page -->

<!-- Slider Section -->
<section id="header-slider" class="section">
  <div id="myCarousel" class="carousel slide" data-ride="carousel"> 
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
       <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>
    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active content-image-right" style='height:100%; background-image: url("/assets/images/slider/slide4.jpg"); '>
        <div class="carousel-caption">
          <p></p>
        </div>
      </div>
      <div class="item content-image-center" style='height:100%; background-image: url("/assets/images/slider/slide5.jpg"); '>
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>
      <div class="item content-image-center" style='height:100%; background-image: url("/assets/images/slider/slide1.jpg"); '>
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>
      <div class="item content-image-right" style='height:100%; background-image: url("/assets/images/slider/slide5.png"); '>
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>
    </div>
    <!-- Controls --> 
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev"> <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span> <span class="sr-only">Previous</span></a> <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next"> <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span> <span class="sr-only">Next</span></a></div>
</section>
<!-- Slider Section --> 
<!-- Service Section -->
<section id="services" class="section services">
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-8 col-sm-8">
        <div class="services-content">
          <h4>About me</h4>
          <br>
          <p>Passionate about building projects and products from scratch. Love making data-driven decisions and maximising the value for customers. </p>
          <p>Started my career in startups, where I helped teams transform their ideas into viable businesses and where I discovered my enthusiasm for product.</p>
          <p>I enjoy bringing people together to solve challenges and to learn from each other. No matter the situation, my analytical mindset pushes me to understand things to the core and improve them.</p>
        </div>
      </div>
      <div class="col-md-4 col-sm-4">
        <div class="services-content">
          <h4>My Skills</h4>
          <p> </p>
          <p> • Analytical
          <br />• Ownership mentality
          <br />• Strategic thinking
          <br />• Problem solving
          <br />• Jack-off-all trades</p>
          <h4>CV</h4>
          <p> </p>
            <p><a href="/assets/files/CV_Lea Gregorka.pdf">Download here</a></p>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- Service Section --> 


<section id="introvideo" class="section introvideo">
   
{% include youtube.html url="https://www.youtube.com/embed/gqd0a2N8AZg" description="" %} 

</section>


<!-- experience grid section -->
{% include home-experience.html %}
<!-- experience grid section -->


<!-- projects grid section -->
{% include home-projects.html %}
<!-- projects grid section -->


<!-- volunteering grid section -->
{% include home-volunteering.html %}
<!-- volunteering grid section -->