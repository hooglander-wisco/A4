
<!-- =========================================================
STEP 1: Add the required HTML5 skeleton
========================================================= -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anna Hooglander's Professional Portfolio</title>
    <link rel="stylesheet" href="cssnuked.css">
    
  </head>

  <body>
    <!-- =========================================================
    STEP 2: Build the “top area” (site name + navigation) using simple HTML
    ========================================================= -->
    <!-- <header class = "site-header">
      <div>
        <h2> Anna Hooglander's professional portfolio website</h2>
        <ul>
          <li><a href="home">Home</a></li>
          <li><a href="portfolio">Portfolio</a></li>
          <li><a href="contact">Contact</a></li>
          <li><a href="blog">Blog</a></li>
        </ul>
        </div>
          </header>
          -->

     <div class="highlighted-heading">
        <h1>Anna Hooglander's Professional Portfolio</h1>
      </div>

      <hr>

      
      <header class = "site-header">
      
      <div class="container header-inner">
        <div class="brand">Simply<span class="dot">.</span></div>


          <nav class="site-nav">
            
            <a href="home">Home</a>
            <a href="portfolio">Portfolio</a>
            <a href="contact">Contact</a>
            <a href="blog">Blog</a>
          </nav>
      </div>
    </header>















    <!-- =========================================================
    STEP 3: Hero section + “Get Started button” as a link
    ========================================================= -->

    
<main>
  <section id="home" class="hero ">
    <div class="hero-overlay">
    <div class="container hero-content">
      <h1>Anna Hooglander</h1>
      <hr>
      <p class="hero-subhead">WHO AM I?</p>
      <img src="/Users/ahooglander/LIS351/lis351-web:/images:/simona-sergi-8HIMR54T8aE-unsplash.jpg" alt="Professional photograph of moutains" style="max-width: 100%; height: auto;">
      <a class="btn btn-dark" href="#featured">Get Started</a>
    </div>
    </div>
  </section>
</main>
    

    <!-- =========================================================
    STEP 4: Features section (3 blocks) + featured content section
    ========================================================= -->
    <section class="features">
  <div class="container features-grid">

    <div class="feature">
      <div class="icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.438 60.438 0 0 0-.491 6.347A48.62 48.62 0 0 1 12 20.904a48.62 48.62 0 0 1 8.232-4.41 60.46 60.46 0 0 0-.491-6.347m-15.482 0a50.636 50.636 0 0 0-2.658-.813A59.906 59.906 0 0 1 12 3.493a59.903 59.903 0 0 1 10.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.717 50.717 0 0 1 12 13.489a50.702 50.702 0 0 1 7.74-3.342M6.75 15a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm0 0v-3.675A55.378 55.378 0 0 1 12 8.443m-7.007 11.55A5.981 5.981 0 0 0 6.75 15.75v-1.5" />
</svg>

        
      </div>
      <h2>Education</h2>
      <p>I am a current junior at UW Madison, studying Information Science with a minor in Data Science and a focus in human psychology. I have a 3.95 GPA and extensive coursework.</p>
    </div>

    <div class="feature">
      <div class="icon">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z" />
</svg>

      </div>
      <h2>Technical Skills</h2>
      <p>I have been working with advanced modeling systems and coding languages since 2021. I started with Python and some Java and did modeling in my engineering coursework. I am proficient in SQL, R, Python, HTML, AutoCAD, and Inventor.</p>
    </div>

    <div class="feature">
      <div class="icon">
       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 9.776c.112-.017.227-.026.344-.026h15.812c.117 0 .232.009.344.026m-16.5 0a2.25 2.25 0 0 0-1.883 2.542l.857 6a2.25 2.25 0 0 0 2.227 1.932H19.05a2.25 2.25 0 0 0 2.227-1.932l.857-6a2.25 2.25 0 0 0-1.883-2.542m-16.5 0V6A2.25 2.25 0 0 1 6 3.75h3.879a1.5 1.5 0 0 1 1.06.44l2.122 2.12a1.5 1.5 0 0 0 1.06.44H18A2.25 2.25 0 0 1 20.25 9v.776" />
</svg>

      </div>
      <h2>Professional Experience</h2>
      <p>I have experience in various technical roles. I worked at Petabit Scale for four years.</p>
    </div>

  </div>
</section>
    
    
<!--     
    
    
    
    
    
    <h2>Education</h2>
    <p> I am a currernt junior at UW madison, and I am an information scienece major with a minor in data scinece, and a focus in human psychology. I have a 3.95 GPA and extenstive coursework </p>
    <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9.813 15.904 9 18.75l-.813-2.846a4.5 4.5 0 0 0-3.09-3.09L2.25 12l2.846-.813a4.5 4.5 0 0 0 3.09-3.09L9 5.25l.813 2.846a4.5 4.5 0 0 0 3.09 3.09L15.75 12l-2.846.813a4.5 4.5 0 0 0-3.09 3.09ZM18.259 8.715 18 9.75l-.259-1.035a3.375 3.375 0 0 0-2.455-2.456L14.25 6l1.036-.259a3.375 3.375 0 0 0 2.455-2.456L18 2.25l.259 1.035a3.375 3.375 0 0 0 2.456 2.456L21.75 6l-1.035.259a3.375 3.375 0 0 0-2.456 2.456ZM16.894 20.567 16.5 21.75l-.394-1.183a2.25 2.25 0 0 0-1.423-1.423L13.5 18.75l1.183-.394a2.25 2.25 0 0 0 1.423-1.423l.394-1.183.394 1.183a2.25 2.25 0 0 0 1.423 1.423l1.183.394-1.183.394a2.25 2.25 0 0 0-1.423 1.423Z">
</svg>

    <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-1">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 0 0 6 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 0 1 6 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 0 1 6-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0 0 18 18a8.967 8.967 0 0 0-6 2.292m0-14.25v14.25">
</svg>


    <h2>Techincal Skills</h2>
    <p> I have been working with advanced modeling systems and coding lanaguges since 2021. I started with python and a small portion of java. And did modeling from my engineerring courswork
        I am proficient in:
         SQL, R, Python, HTML, Autocad, Inventor, and </p>
    <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-1">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.182 15.182a4.5 4.5 0 0 1-6.364 0M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0ZM9.75 9.75c0 .414-.168.75-.375.75S9 10.164 9 9.75 9.168 9 9.375 9s.375.336.375.75Zm-.375 0h.008v.015h-.008V9.75Zm5.625 0c0 .414-.168.75-.375.75s-.375-.336-.375-.75.168-.75.375-.75.375.336.375.75Zm-.375 0h.008v.015h-.008V9.75Z">
</svg>


    <h2>Proffesssional Experince </h2>
    <p> I have experience in various technical roles, i worked at Petabite scale for 4 years </p>
    <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-1">
  <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z">
</svg> -->


<section id="featured" class="featured">
  <div class="container">
    <h2 class="section-title">Featured Content</h2>
    <p class="section-lede">
      Last semester I worked on an HTML/CSS project constructing a
      restaurant website that was fully navigable.
    </p>

    <div class="media">
      <img
        src="/Users/ahooglander/LIS351/lis351-web:/images:/restaurant.jpg"
        alt="Restaurant website project created for an HTML and CSS class"
        style="max-width: 50%; height: auto;"
      >
    </div>

    <a class="btn btn-dark" href="#portfolio">View More</a>
  </div>
</section>


    <!-- =========================================================
    STEP 5: Two secondary content blocks + CTA section 
    ========================================================= -->
    
    
<section id="portfolio" class="secondary">
  <div class="container secondary-grid">

    <!-- <article class="card">
      <div class="card-text">
        <h3>Campus Involvement</h3>
        <p>Here are my campus involvement activities. I have been a member of Zeta Tau Alpha and have held various leadership roles.</p>
        <a class="btn btn-outline" href="#contact">View More</a>
      </div>
      <div class="card-image img-a"></div>
    </article> -->
    <article class="card">
        <div class="card-text">
            <h3>Campus Involvement</h3>
            <p>Here are my campus involvement activities  I have been a member of Zeta Tau Alpha and have held various leadership roles.</p>
            <a class="btn btn-outline" href="#contact">View More</a>
            
        </div>
        <div class="card-image img-a" float="right"></div>
    </article>

    <article class="card">
      <div class="card-text">
        <h3>Personal Passion Projects</h3>
        <p>I am using this space to highlight some of the more unconventional projects I have worked on.</p>
        <a class="btn btn-outline" href="#contact">View More</a>
      </div>
      <div class="card-image img-b"></div>
    </article>

    <!-- <article class="card">
      <div class="card-text">
        <h3>Personal Passion Projects</h3>
        <p>I am using this space to highlight some of the more unconventional projects I have worked on.</p>
        <a class="btn btn-outline" href="#contact">View More</a>
      </div>
      <div class="card-image img-b"></div>
    </article> -->

  </div>
</section>

    
    
    
    
<!--     
    <h3>Campus Involvement</h3>
    <p> Here are my campus involvement activities.I have been a member of Zeta Tau Alpha for the past three years and have held various leadership roles.</p>
    <a class="btn btn-dark" href="#featured">view more for campus involvement</a>

    <h3>Personal Passion Projects</h3>
    <p> A well rounded perosn is not just composed with techical skills. I am using this space here as an oppuirntiy to highlight some of the more unconvetional things that I have used my time on.  </p>
    <a class="btn btn-dark" href="#featured">view more for personal passion projects</a>
    <p>different project types</p>
    <ul>
    <li>Python</li>
    <li>R</li>
    <li>Data Analysis</li>
    <li>GIS</li>
    <li>Information Science</li>
</ul> -->
    <br>

    <a class="btn btn-dark" href="#calltoaction">HEARD ENOUGH? Here is my call to action </a>

    <!-- =========================================================
    STEP 6: Footer 
    ========================================================= -->
  
  
    <footer>
    <div class="container footer-inner">
      <p>Copyright &copy; ALH2026</p>
      <nav>
      <a href="resume.pdf">View My Résumé</a>
      <a href="https://www.linkedin.com/anna_hooglander">LinkedIn</a>
      <a href="mailto:hooglander@wisc.edu">Email Me</a>
    </nav>
      <a class="btn btn-dark" href="#termsandservices">Terms and Services</a>
    </div>
  </footer>




  </body>
</html>
