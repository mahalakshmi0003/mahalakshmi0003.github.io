<!DOCTYPE html>
<html>
  <title>MY PORTFOLIO</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css?family=Montserrat"
  />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
  />
  <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    /* Set the width of the sidebar to 120px */
    .w3-sidebar {width: 120px;background: #222;}
    /* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
    #main {margin-left: 120px}
    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {#main {margin-left: 0}}
  </style>
  <body class="w3-black">
    <!-- Icon Bar (Sidebar - hidden on small screens) -->
    <nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
      <!-- Avatar image in top left corner -->
      <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
        <i class="fa fa-home w3-xxlarge"></i>
        <p>HOME</p>
      </a>
      <a
        href="#about"
        class="w3-bar-item w3-button w3-padding-large w3-hover-black"
      >
        <i class="fa fa-user w3-xxlarge"></i>
        <p>ABOUT</p>
      </a>
      <a
        href="#contact"
        class="w3-bar-item w3-button w3-padding-large w3-hover-black"
      >
        <i class="fa fa-envelope w3-xxlarge"></i>
        <p>CONTACT</p>
      </a>
    </nav>

    <!-- Navbar on small screens (Hidden on medium and large screens) -->
    <div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
      <div
        class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small"
      >
        <a href="#" class="w3-bar-item w3-button" style="width:25% !important"
          >HOME</a
        >
        <a
          href="#about"
          class="w3-bar-item w3-button"
          style="width:25% !important"
          >ABOUT</a
        >
        <a
          href="#contact"
          class="w3-bar-item w3-button"
          style="width:25% !important"
          >CONTACT</a
        >
      </div>
    </div>

    <!-- Page Content -->
    <div class="w3-padding-large" id="main">
      <!-- Header/Home -->
      <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
        <h1 class="w3-jumbo">
          <span class="w3-hide-small">I'm</span> Mahalakshmi V
        </h1>
        <p>FULL STACK DEVELOPER</p>
      </header>

      <!-- About Section -->
      <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
        <h2 class="w3-text-light-grey">HI👋</h2>
        <!-- <hr style="width:200px" class="w3-opacity"> -->
        <p>
          Hello! I’m Mahalakshmi, a passionate second-year Information
          Technology student at Sri Krishna College of Engineering and
          Technology. With a strong foundation in web development and
          programming, I’m eager to leverage my skills and knowledge to create
          innovative and efficient solutions
        </p>
        <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
        <p class="w3-wide">web design</p>
        <div class="w3-white">
          <div class="w3-dark-grey" style="height:28px;width:60%"></div>
        </div>
        <p class="w3-wide">sql</p>
        <div class="w3-white">
          <div class="w3-dark-grey" style="height:28px;width:70%"></div>
        </div>
        <p class="w3-wide">c++ and java</p>
        <div class="w3-white">
          <div class="w3-dark-grey" style="height:28px;width:50%"></div>
        </div>
        <br />
      </div>

      <button class="w3-button w3-light-grey w3-padding-large w3-section">
        <i class="fa fa-download"></i> Download Resume
      </button>
      <!-- Contact Section -->
      <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
        <h2 class="w3-text-light-grey">Contact Me</h2>
        <hr style="width:200px" class="w3-opacity" />

        <div class="w3-section">
          <p>
            <i
              class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"
            ></i
            >Coimbatore
          </p>
          <p>
            <i
              class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"
            ></i>
            Phone: +91 8838491465
          </p>
          <p>
            <i
              class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"
            >
            </i>
            Email: mahalakshmi@gmail.com
          </p>
        </div>
        <br />
        <p>Let's get in touch. Send me a message:</p>

        <form action="/action_page.php" target="_blank">
          <p>
            <input
              class="w3-input w3-padding-16"
              type="text"
              placeholder="Name"
              required
              name="Name"
            />
          </p>
          <p>
            <input
              class="w3-input w3-padding-16"
              type="text"
              placeholder="Email"
              required
              name="Email"
            />
          </p>
          <p>
            <input
              class="w3-input w3-padding-16"
              type="text"
              placeholder="Subject"
              required
              name="Subject"
            />
          </p>
          <p>
            <input
              class="w3-input w3-padding-16"
              type="text"
              placeholder="Message"
              required
              name="Message"
            />
          </p>
          <p>
            <button
              class="w3-button w3-light-grey w3-padding-large"
              type="submit"
            >
              <i class="fa fa-paper-plane"></i> SEND MESSAGE
            </button>
          </p>
        </form>
        <!-- End Contact Section -->
      </div>

      <!-- Footer -->
      <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
        <i class="fa fa-instagram w3-hover-opacity"></i>
        <i class="fa fa-snapchat w3-hover-opacity"></i>
        <i class="fa fa-github w3-hover-opacity"></i>
        <i class="fa fa-twitter w3-hover-opacity"></i>
        <i class="fa fa-linkedin w3-hover-opacity"></i>

        <!-- End footer -->
      </footer>

      <!-- END PAGE CONTENT -->
    </div>
  </body>
</html>
