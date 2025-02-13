# LIS-500-Project-2
<!DOCTYPE html>
<html lang="en">
 <head>
   <meta charset="UTF-8" />
   <meta http-equiv="X-UA-Compatible" content="IE=edge" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <title>LIS500Project</title>
   <link rel="stylesheet" href="stylepage.css" />
 </head>
 <body>
   <nav>
     <div class="logo">LIS 500 Project</div>
     <ul class="nav-links">
       <li><a href="#Welcome">Welcome</a></li>
       <li><a href="#about">About</a></li>
       <li><a href="#resources">Resources</a></li>
       <li><a href="#tech-hero">Tech Hero</a></li>
      </ul>
   </nav>
    <!-- Splash Page -->
   <section id="home" class="splash">
     <div class="container">
       <h1>Welcome!</h1>
       <a href="#about" class="button">Learn More</a>
     </div>
   </section>

   </div>
      <div id="description">
       <p id="joan" class="description">Hi, I’m Joan Lee. I am from Seoul, Korea but I have lived in multiple countries: Taiwan, and the US. I am pursuing a double major in Information Science and Communication Arts with a minor in Digital Studies at the University of Wisconsin-Madison.</p>
       <p id="madison" class="description">I’m originally from Milwaukee, WI. I’m a junior studying Information Science. I’m minoring in Digital Studies, Digital Media Analytics, Sports Communication and Graphic Design. This semester in addition to LIS 500 Code and Power I’m taking LIS 472 Introduction to Web Development, LIS 640 Generative AI, JOURN 175 Digital Media Fluency, and ATM OCN 102 Climate Change.</p>
       <p id="ann" class="description">Hi, I’m Ann Teoh. I am from Kuala Lumpur Malaysia I am senior in Information Science with a minor in Digital Studies at UW.
       </p>
     </div>
   </div>
 </section>
 
  <script>
   function showDescription(person) {
     document.querySelectorAll('.description').forEach(desc => desc.style.display = 'none');
     document.getElementById(person).style.display = 'block';
   }
 </script>


<!-- About Me Section -->
<section id="about">
   <div class="container">
     <h2>About Us</h2>
      <div class="buttons">
       <button class="profile-btn" onclick="showDescription('joan')">Joan Lee</button>
       <button class="profile-btn" onclick="showDescription('madison')">Madison Sveum</button>
       <button class="profile-btn" onclick="showDescription('ann')">Ann Teoh</button>

    <!-- Resources Page (Implicit Bias) -->
   <section id="resources">
     <div class="container">
       <h2>Resource Page</h2>
       <p>Learn more about implicit bias and intersectionality. Click the links below! </p>


     <h3>Journals</h3>
       <ul>
         <li><a href="https://www.jstor.org/journal/jinte">The Journal of Intersectionality</a></li>
         <li><a href="Virtual Special Issue - Intersectionality">Virtual Special Issue - Intersectionality</a></li>
         <li><a href="https://chicagounbound.uchicago.edu/cgi/viewcontent.cgi?article=1052&context=uclf">Demarginalizing the Intersection of Race and Sex</a></li>


         <h3>Books</h3>


         <li><a href="https://scholarship.law.columbia.edu/books/255/">On Intersectionality : Essential Writings</a></li>
         <li><a href="https://www.dukeupress.edu/intersectionality-as-critical-social-theory">Intersectionality as Critical Social Theory</a></li>
         <li><a href="https://www.haymarketbooks.org/books/780-freedom-is-a-constant-struggle">Freedom is a constant struggle</a></li>
        
         <h3>Videos</h3>

