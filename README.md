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




<!-- About Me Section -->
<section id="about">
   <div class="container">
     <h2>About Us</h2>
      <div class="buttons">
       <button class="profile-btn" onclick="showDescription('joan')">Joan Lee</button>
       <button class="profile-btn" onclick="showDescription('madison')">Madison Sveum</button>
       <button class="profile-btn" onclick="showDescription('ann')">Ann Teoh</button>
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


         <li><a href="https://www.youtube.com/watch?v=O1islM0ytkE">What is Intersectionality?</a></li>
         <li><a href="https://youtu.be/akOe5-UsQ2o?si=DLD1gXfG9l3qm7oB">The Urgency of Intersectionality</a></li>
         <li><a href="https://www.khanacademy.org/test-prep/mcat/social-inequality/social-class/v/intersectionalityB">Intersectionality</a></li>


         <h3>Podcasts</h3>


         <li><a href="https://podcasts.apple.com/us/podcast/intersectionality-matters/id1441348908">Intersectionality Matters!</a></li>
         <li><a href="https://www.npr.org/sections/codeswitch/">Code Switch-Race. In your face</a></li>
         <li><a href="https://creators.spotify.com/pod/show/minda-harts/episodes/Intersectionality-and-Allyship-e2hska/a-a6ao6d">Secure the Seat</a></li>


       </ul>
     </div>
   </section>


   <!-- Tech Hero Section -->
   <section id="tech-hero">
     <div class="container">
       <h2>Tech Hero</h2>
       <p> Dishanta Kpatrick is a self taught coder who made her way to work at Intuit MailChimp as a front end developer. She started coding in high school through 4-H. When her teacher, Mrs. Smith noticed her potential, and encouraged her to create a website for the local 4-H program. She went to state school after highschool and started to study but ended up not liking it and entering the workforce. 
	   <p> She was looking for a job when she came across Intuit MailChimp. They were hiring for their Tech Support team. She learned how to code HTML, JavaScript, CSS, and API. She then found that she wanted to create a career in tech, and ended up going to a full-stack web developers boot camp at Georgia Tech. Over six months, she gained the necessary skills. She began to apply for jobs but found that her certificate wasn’t enough. She went back to school for cybersecurity and is currently working on her degree.
	   <p> Not even a year later, an  <a href = "https://www.intuit.com/careers/programs/career-pathways/?cid=dis_pocit_clicks_us_eb-media_aw_article-dishanta%7CURM_link%7Cnone_intuit-talent"> apprenticeship program </a> was started at MailChimp. Out of 50 applicants, only her and 4 others got the placement. That was her journey to engineering. She can be seen as a hero for her untraditional path to tech. Kpatrick shows others who have a non-traditional educational background that they can do it too. 
	   <p> <a href ="https://peopleofcolorintech.com/articles/interview-dishanta-kpatricks-unique-path-from-self-taught-coder-to-front-end-engineer-at-intuit-mailchimp/"> Read more about Dishanta Kpatrick’s story here. </a> </p>
	   </p>
     </div>
   </section>




   <footer>
     <p>&copy; Joan Lee, Madison Sveum, Ann Teoh. LIS 500 Project2</p>
   </footer>
 </body>
</html>


