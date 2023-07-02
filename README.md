<!DOCTYPE html>
<html>
  <head>
    <title>K S Sweetha - Portfolio</title>
    <link rel="stylesheet" href="./style.css"/>
    <script src="./script.js"></script>
  </head>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          K S Sweetha
          <div class="contact_info">
           kssweetha@jeemail.com
        </div>
        <div style="clear:both;"></div>
        <div class="contact_info">
        +0123456789

        </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <a class="topmenu" href="#skills">Skills</a>
          <a class="topmenu" href="#projects">Projects</a>
          <a class="topmenu" href="#recommendations">Recommendations</a>
          
          <!-- Add the links for Skills, Projects and Recommendation here -->

        </div>
      </div>    
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
     <div>
        <img src="https://miro.medium.com/max/1400/1*qdAW1TjCN57h1lbuuzvchg.gif" class="profile_image"/>
      </div>

      <div>
          <h1>
            Hi, I'm KSSweetha! <img src="https://twemoji.maxcdn.com/2/72x72/1f44b.png" width="60px"/>
          </h1>
          <p>
            I like programming.I love front end languages a lot.
          </p>
      </div>
    </section>
              
    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear:both;"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>HTML</h6>
          <p>1 years experience</p>
        </div>  

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg"/>
          <h6>JavaScript</h6>
          <p>1 years experience</p>
        </div>  

        <!-- Add more skills here -->
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>JAVA</h6>
          <p>1 years experience</p>
        </div>
        
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>SQL</h6>
          <p>4 years experience</p>
        </div>
        
        <div class="skill">
          <img src="html_finalprojimages/html5.png"/>
          <h6>Python</h6>
          <p>1 years experience</p>
        </div>
        
      </div>
    </section>
          
    <!-- Projects -->
    <section class="projects" id="projects">
      <h2>
        Projects
      </h2>
      <div style="clear:both;"></div>

        <div id="projects-container" class="projects-container">
          <div class="project-card">
            <h3>Machine Learning</h3>
            <ul>
              <li>Image based plant based disease detection</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Deep learning</h3>
            <ul>
              <li>Developed a image based plant disease detection </li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Website</h3>
            <ul>
              <li>Created website for a new public fans who can write positive review</li>
            </ul>
          </div>
    </div>
    </section>
    <div style="clear:both;"></div>

    <!-- Recommendations -->
    <section id="recommendations">
      <h2>Recommendations</h2>
      <div style="clear:both;"></div>
      <div class="all_recommendations" id="all_recommendations">
        <div class="recommendation">
          <span>“</span>
          Sweetha is a very good programmer.
          She has good knowledge in programming languages.
          <span>“</span>
        </div>
        <div class="recommendation">
          <span>“</span>
          She is good at working in projects and her creative idea helps a lot in website design.
          <span>”</span>
        </div>
        <div class="recommendation">
          <span>“</span>
          The work which we done along with her was really completed on time.
          <span>”</span>
        </div>
      </div>
    </section>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>          
          <input type="text" placeholder="Name (Optional)"> <br/>
          <textarea id="new_recommendation" cols="500" rows="10" placeholder="Message"></textarea>
          <div class="flex_center">
            <button id="recommend_btn" onclick="addRecommendation()">Submit</button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <!--Add the code here for the logo to appear and the icon to be actionable-->
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.25l-3-3m0 0l-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
      </a>
    </div>

    <div class="popup" id="popup" class="flex_center">
      <img src="html_finalprojimages/checkmark--outline.svg"/>
      <h3><!-- Add appropriate text here-->
      Thanks for leaving a recommendation!</h3>
      <button onclick="showPopup(false)">Ok</button>
    </div>
  </body>
</html>

