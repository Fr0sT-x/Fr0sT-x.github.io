Shuji Nakamura - Personal Website
<link
  href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap"
  rel="stylesheet"
/>
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
/>

  html,
  body {
    font-family: "Roboto", sans-serif;
    margin: 0;
    padding: 0;
    height: 100vh; /* Ensure the body takes the full height of the viewport */
    background: linear-gradient(
      to bottom right,
      #e0f7fa,
      #b2ebf2
    ); /* Use a full gradient */
    background-attachment: fixed; /* Keep the gradient fixed during scroll */
  }

  header {
    background: #2c3e50; /* Dark slate gray */
    color: #ffffff;
    padding: 20px 0;
    text-align: center;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
  }

  nav {
    display: flex; /* Ensure flexbox is used */
    justify-content: center; /* Center the items */
    flex-wrap: wrap; /* Allow items to wrap */
    margin: 20px 0;
  }

  nav a {
    margin: 0 15px;
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
    display: flex; /* Flexbox to align icon and text */
    align-items: center; /* Center icon and text */
  }

  nav a i {
    margin-right: 8px; /* Space between icon and text */
    font-size: 1.2em; /* Adjust icon size */
  }

  nav a:hover {
    color: #f39c12; /* Light gold */
  }

  .container {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    color: #34495e; /* Dark gray */
    flex-direction: column;
    padding: 20px;
  }

  section {
    margin: 20px;
    padding: 20px;
    background: rgba(255, 255, 255, 0.9); /* Slightly transparent white */
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 90%;
    transition: background-color 0.3s;
  }

  h3 {
    font-size: 1.8rem; /* Adjust h3 size */
    color: #f39c12; /* Light gold color */
    margin-top: 10px;
    border-bottom: 2px solid #f39c12; /* Light gold */
    padding-bottom: 10px;
  }

  .highlight {
    background-color: #f1c40f; /* Light gold highlight */
  }

  .container {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    color: #34495e; /* Dark gray */
    flex-direction: column;
    padding: 20px;
  }

  #progress-bar {
    position: fixed;
    top: 0;
    left: 0;
    height: 5px;
    width: 100%;
    background: linear-gradient(
      to right,
      #3220d3,
      #c51098
    ); /* Gradient color */
    z-index: 9999; /* Ensure it's on top */
    transition: width 0.1s ease; /* Smooth transition */
  }
  .about-content {
    display: flex;
    align-items: center; /* Vertically align items */
  }

  .about-content p {
    flex: 1; /* Allow paragraph to take remaining space */
    margin-right: 20px; /* Add space between text and image */
  }

  .about-image {
    max-width: 200px; /* Set a maximum width for the image */
    height: auto; /* Maintain aspect ratio */
  }

  #dynamic-heading {
    display: inline;
    font-size: 2.5rem; /* Larger font size */
    font-weight: 700; /* Bold font */
    color: #ffffff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Soft shadow for depth */
  }

  .cursor {
    display: inline-block;
    width: 5px; /* Cursor width */
    height: 1.9em; /* Cursor height */
    background-color: rgb(0, 0, 0); /* Cursor color */
    animation: blink 0.7s step-end infinite; /* Blinking effect */
    margin-left: 5px; /* Space between text and cursor */
  }

  @keyframes blink {
    50% {
      background-color: transparent;
    } /* Make cursor invisible */
  }










    Researcher in Optoelectronics & Semiconductor Technology

  ### 


    <a href="#about" onclick="highlight('about')"
      >_ About Me</a
    >
    <a href="#education" onclick="highlight('education')"
      >_ Educational Background</a
    >
    <a href="#experience" onclick="highlight('experience')"
      >_ Experience</a
    >
    <a href="#publications" onclick="highlight('publications')"
      >_ Publications</a
    >
    <a href="#awards" onclick="highlight('awards')"
      >_ Awards</a
    >
    <a href="#projects" onclick="highlight('projects')"
      >_ Projects</a
    >
    <a href="#membership" onclick="highlight('membership')"
      >_ Membership</a
    >
    <a href="#research" onclick="highlight('research')"
      >_ Research Areas</a
    >
    <a href="#events" onclick="highlight('events')"
      >_ Events</a
    >
    <a href="#presentations" onclick="highlight('presentations')"
      >_ Presentations</a
    >
    <a href="#courses" onclick="highlight('courses')"
      >_ Courses</a
    >
    <a href="#contact" onclick="highlight('contact')"
      >_ Contact</a
    >





    ### About Me


        Welcome to my personal page! I’m Shuji Nakamura, a researcher and
        inventor known for my contributions to optoelectronics and
        semiconductor technology. My work focuses on developing
        energy-efficient lighting solutions, particularly through
        solid-state lighting. I’m excited to share my research journey and
        insights with you. I am passionate about advancing the field of
        optoelectronics. With a background in physics and engineering, I aim
        to bridge theoretical research with practical applications. My most
        notable contributions include the invention of blue LEDs, which have
        transformed lighting technologies and paved the way for
        energy-efficient solutions worldwide.

      <img
        src="ucsb_nakamura.jpg"
        alt="Shuji Nakamura"
        class="about-image"
      />




    ### Educational Background

      I earned my Ph.D. in Materials Science from the University of
      California, Santa Barbara, in 1994. My educational background laid the
      foundation for my research interests in semiconductor materials and
      devices. During my studies, I had the opportunity to collaborate with
      leading experts, which significantly shaped my career.




    ### Experience

      I began my research career at UCSB, where I focused on developing
      light-emitting diodes (LEDs) and laser diodes. I later held positions
      at various institutions, including a role as a professor in the
      Materials Department at UCSB. My experience spans academia and
      industry, allowing me to contribute to significant advancements in
      lighting technology.




    ### Paper/Patent Publications


        I have authored over 400 research papers. My publications cover
        topics such as blue LEDs, laser diodes, and their applications in
        energy-efficient lighting. Sharing my findings has been a key part
        of my mission to advance the field.In addition to my extensive
        research papers, I hold over 1,000 patents, many of which have
        significantly influenced the field of optoelectronics. My most
        notable patents include innovations in blue LED technology, which
        have enabled the development of energy-efficient lighting solutions
        and display technologies. Each patent represents a step forward in
        understanding and utilizing semiconductor materials for practical
        applications. Some of my patents focus on improving the efficiency
        and longevity of LED devices, while others explore novel materials
        and fabrication techniques. I have collaborated with various
        industry partners to translate my research into commercially viable
        products, bridging the gap between academia and industry. I am
        committed to sharing my findings and inventions with the scientific
        community, as I believe that collaboration fosters innovation. My
        work continues to inspire new research directions, and I am excited
        to see how these advancements will contribute to a more sustainable
        future. Through these patents, I aim to influence both current
        technologies and the next generation of optoelectronic devices.

      ![patents](image-112.png)




    ### Awards and Achievements


        I was awarded the Nobel Prize in Physics in 2014 for the invention
        of efficient blue light-emitting diodes, which have revolutionized
        lighting technology. Additionally, I have received numerous other
        accolades, including the IEEE Medal of Honor and the Nishina
        Memorial Prize, recognizing my contributions to semiconductor
        technology and energy conservation.

      <img
        src="ne-nakamura-king-442-landscape-gallery.webp"
        alt="Prize"
        class="about-image"
      />




    ### Projects

      Throughout my career, I have led several impactful projects, including
      the development of high-brightness LEDs that are widely used in
      commercial and residential lighting. I am currently involved in
      projects aimed at improving the efficiency of solid-state lighting and
      exploring new materials to enhance device performance.




    ### Membership

      I am a member of several professional organizations, including the
      Institute of Electrical and Electronics Engineers (IEEE) and the
      Optical Society of America (OSA). These memberships provide me with
      opportunities to collaborate with fellow researchers and stay engaged
      with the latest developments in optoelectronics.




    ### Research Thrust Area

      My primary research focus is on solid-state lighting, particularly the
      development of new materials and devices for energy-efficient lighting
      applications. I am dedicated to exploring innovative approaches that
      can lead to sustainable lighting solutions for a wide range of
      applications.




    ### List of Events (Organized/Attended)

      I have organized and participated in numerous conferences and
      workshops related to optoelectronics and semiconductor technology.
      These events include the International Conference on LED Lighting and
      the SPIE Photonics West, where I have had the opportunity to share my
      research and collaborate with other experts in the field.




    ### Poster/Paper Presentation

      I have presented my research at various national and international
      conferences, showcasing my work on blue LEDs and their applications.
      Engaging with fellow researchers during these presentations has been
      invaluable, allowing for the exchange of ideas and constructive
      feedback that helps shape future research.




    ### Courses Completed

      Throughout my academic journey, I have completed various courses in
      materials science, semiconductor physics, and optoelectronics. These
      courses have equipped me with the knowledge and skills necessary to
      innovate in the field and have fueled my passion for research and
      development in lighting technologies.




    ### Contact Address

      I welcome inquiries and collaboration opportunities related to my
      research in optoelectronics and solid-state lighting. If you have
      questions, suggestions, or would like to discuss potential projects,
      please feel free to reach out. You can contact me via email at
      shuji143@gmail.com. I look forward to connecting with fellow
      researchers, students, and industry professionals who share a passion
      for advancing lighting technology and energy efficiency.





  window.onscroll = function () {
    var scrollTop =
      document.documentElement.scrollTop || document.body.scrollTop;
    var windowHeight =
      document.documentElement.scrollHeight -
      document.documentElement.clientHeight;
    var scrollPercent = (scrollTop / windowHeight) * 100;
    document.getElementById("progress-bar").style.width =
      scrollPercent + "%";
  };



  function highlight(sectionId) {
    const section = document.getElementById(sectionId);
    const originalColor = section.style.backgroundColor;

    // Scroll to the section smoothly
    section.scrollIntoView({ behavior: "smooth" });

    // Add highlight class
    section.classList.add("highlight");

    // Remove highlight after a short duration
    setTimeout(() => {
      section.classList.remove("highlight");
    }, 1000); // Highlight duration
  }
  const heading = document.getElementById("dynamic-heading");
  const cursor = document.getElementById("cursor");
  const initialText = "Hi, I am Shuji Nakamura";
  const middleText = "Welcome to my Webpage!";
  const finalText = "Shuji Nakamura";

  let index = 0;

  function typeOut(text, callback) {
    if (index < text.length) {
      heading.textContent += text.charAt(index);
      index++;
      setTimeout(() => typeOut(text, callback), 75);
    } else if (callback) {
      callback();
    }
  }

  function deleteOut(callback) {
    if (index > 0) {
      heading.textContent = heading.textContent.slice(0, -1);
      index--;
      setTimeout(() => deleteOut(callback), 75);
    } else if (callback) {
      callback();
    }
  }

  function startTyping() {
    typeOut(initialText, () => {
      setTimeout(() => {
        deleteOut(() => {
          heading.textContent = ""; // Clear the text
          index = 0; // Reset index for middle typing
          typeOut(middleText, () => {
            setTimeout(() => {
              deleteOut(() => {
                heading.textContent = ""; // Clear the text
                index = 0; // Reset index for final typing
                typeOut(finalText, () => {
                  cursor.style.display = "none"; // Hide cursor after typing is complete
                });
              });
            }, 1000); // Pause before deleting middle text
          });
        });
      }, 1000); // Pause before deleting initial text
    });
  }

  startTyping();

<footer
  style="
    text-align: center;
    padding: 20px;
    background: #2c3e50;
    color: #fff;
  "
>
  Connect with me on social media:
  <a href="https://linkedin.com" style="color: #fff; margin: 0 10px"
    >LinkedIn</a
  >
  <a href="https://twitter.com" style="color: #fff; margin: 0 10px"
    >Twitter</a
  >
  &copy; 2024 Shuji Nakamura. All rights reserved.
