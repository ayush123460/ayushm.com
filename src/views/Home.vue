<template>
<div class="container">
  <main>
    <div class="content">
      <div class="tag">
        I design and build
        <br>
        interfaces for Humans.
      </div>
      <div class="para">
        <p>I make robust, easy to use systems and applications centered around humans. I believe simplicity is the way forward for modern systems and apps.</p>
      </div>
      <div class="cta">
        <a href="#work" class="btn">See my work</a>
        <a href="#contact" class="btn btn-secondary">Discuss a project</a>
      </div>
    </div>
    <div class="illustration">
      <img src="@/assets/illustration.png" alt="Illustration">
    </div>
  </main>

  <div class="title" id="work">
    <div class="sub">Here's some of my</div>
    Work / Projects
  </div>

  <section class="work">
    <div class="panel">
      <div class="panel__body">
        <div class="body__number">1</div>
        <div class="body__title">APL Esports - Website, Overlays, CMS</div>
        <div class="body__content">
          <p>APL Esports is the premier tournament organizer for the SEA region for the game Rocket League with their latest addition being sponsored by Psyonix, the game’s developer, for a grand total of $45,500.</p>
        </div>
        <div class="body__cta">
          <a href="https://aplesports.com" target="_blank" class="btn">Visit Website</a>
        </div>
      </div>
      <div class="panel__image">
        <img src="@/assets/apl.png" alt="">
      </div>
    </div>
    <div class="panel panel-sec">
      <div class="panel__body">
        <div class="body__number">2</div>
        <div class="body__title">Advitya 2020, VIT Bhopal - Fest Website</div>
        <div class="body__content">
          <p>Advita is VIT Bhopal University's premier tech and cultural fest. 2020's edition had a lot of special things planned but unfortunately shut down due to the global pandemic.</p>
        </div>
        <div class="body__cta">
          <a href="http://advitya.net" target="_blank" class="btn">Visit Website</a>
          <a href="https://github.com/ayush123460/advitya2020" target="_blank" class="btn btn-secondary">View on Github</a>
        </div>
      </div>
      <div class="panel__image">
        <img src="@/assets/advitya.png" alt="">
      </div>
    </div>
    <div class="panel">
      <div class="panel__body">
        <div class="body__number">3</div>
        <div class="body__title">CPGC - Cross Platform Git Client</div>
        <div class="body__content">
          <p>CPGC is aimed at beginners to start their git and version control journey. This application is still under development and it aims to be as end user friendly as possible while explaining how things run in the background.</p>
        </div>
        <div class="body__cta">
          <a href="https://github.com/ayush123460/cpgc" target="_blank" class="btn btn-secondary">View on Github</a>
        </div>
      </div>
      <div class="panel__image">
        <img src="@/assets/cpgc.png" alt="">
      </div>
    </div>
  </section>

  <div class="title" id="about">
    <div class="sub">Know some more</div>
    About Me
  </div>

  <section class="about">
    <div class="profile">
      <img src="@/assets/logo.png" alt="Logo">
    </div>
    <div class="content">
      <div class="heading">
        <p>
          Hello, I'm
          <br>
          <span>Ayush Mukherjee.</span>
        </p>
      </div>
      <div class="body">
        <p>I am a passionate and inquisitive software engineer with multiple years of experience building high performance web and mobile applications. I am a third year university student and am looking for internships to further develop my skills and explore what the industry continues to function on.</p>
      </div>
      <div class="cta">
        <a href="/resume.pdf" class="btn">Download Resume</a>
        <a href="#contact" class="btn btn-secondary">Contact Me</a>
      </div>
    </div>
  </section>

  <div class="title" id="skills">
    <div class="sub">Here's what I know</div>
    Skills
  </div>

  <section class="skills">
    <div class="list">
      <div class="list__heading">
        Full Stack Web Developer &amp; Designer
      </div>
      <div class="list__body">
        <p>
          <ul>
            <li>HTML5, CSS3, Javascript / ES6</li>
            <li>Bootstrap 4</li>
            <li>Vue JS, Vuetify</li>
            <li>PHP 7, Laravel Framework</li>
            <li>Node JS</li>
            <li>Electron JS</li>
            <li>Ionic Framework</li>
            <li>MySQL, Postgres</li>
            <li>Docker</li>
          </ul>
        </p>
      </div>
    </div>
    <div class="list">
      <div class="list__heading">
        Software Engineering
      </div>
      <div class="list__body">
        <p>
          <ul>
            <li>C / 98</li>
            <li>C++ / 11</li>
            <li>Java SE 8</li>
            <li>Python 3</li>
            <li>Linux SysAdmin</li>

          </ul>
        </p>
      </div>
    </div>
    <div class="list">
      <div class="list__heading">
        Interests
      </div>
      <div class="list__body">
        <p>
          <ul>
            <li>Virtualization</li>
            <li>Systems Design</li>
            <li>Web Assembly</li>
          </ul>
        </p>
      </div>
    </div>
  </section>

  <div class="title" id="contact">
    <div class="sub">Ways to</div>
    Contact Me
  </div>

  <section class="contact">
    <div class="form">
      <form id="contact-form">
        <div class="input-group">
          <label for="name">Name:</label>
          <input type="text" name="name" v-model="name" required autocomplete="off">
        </div>
        <div class="input-group">
          <label for="email">Email:</label>
          <input type="email" name="email" v-model="email" required autocomplete="off">
        </div>
        <div class="input-group">
          <label for="message">Message:</label>
          <textarea v-model="message"></textarea>
        </div>

        <div class="input-group">
          <input type="submit" class="btn" value="Submit" @click="submitForm()">
        </div>
      </form>
    </div>
    <div class="socials">
      <span>I'm also available via:</span>
      <span><img width="25px" src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMjIgNXYxNGgtMjB2LTE0aDIwem0yLTJoLTI0djE4aDI0di0xOHptLTIgMTZsLTYuNTI2LTYuNjE4LTMuNDQ1IDMuNDgzLTMuNDE4LTMuNTI1LTYuNjExIDYuNjYgNS4wNTEtOC01LjA1MS02IDEwLjAyOSA3LjQ0NiA5Ljk3MS03LjQ0Ni00Ljk5OCA2LjAxIDQuOTk4IDcuOTl6Ii8+PC9zdmc+"><a href="mailto:me@ayushm.com">me@ayushm.com</a></span>
      <span><img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTkgMGgtMTRjLTIuNzYxIDAtNSAyLjIzOS01IDV2MTRjMCAyLjc2MSAyLjIzOSA1IDUgNWgxNGMyLjc2MiAwIDUtMi4yMzkgNS01di0xNGMwLTIuNzYxLTIuMjM4LTUtNS01em0tLjEzOSA5LjIzN2MuMjA5IDQuNjE3LTMuMjM0IDkuNzY1LTkuMzMgOS43NjUtMS44NTQgMC0zLjU3OS0uNTQzLTUuMDMyLTEuNDc1IDEuNzQyLjIwNSAzLjQ4LS4yNzggNC44Ni0xLjM1OS0xLjQzNy0uMDI3LTIuNjQ5LS45NzYtMy4wNjYtMi4yOC41MTUuMDk4IDEuMDIxLjA2OSAxLjQ4Mi0uMDU2LTEuNTc5LS4zMTctMi42NjgtMS43MzktMi42MzMtMy4yNi40NDIuMjQ2Ljk0OS4zOTQgMS40ODYuNDExLTEuNDYxLS45NzctMS44NzUtMi45MDctMS4wMTYtNC4zODMgMS42MTkgMS45ODYgNC4wMzggMy4yOTMgNi43NjYgMy40My0uNDc5LTIuMDUzIDEuMDgtNC4wMyAzLjE5OS00LjAzLjk0MyAwIDEuNzk3LjM5OCAyLjM5NSAxLjAzNy43NDgtLjE0NyAxLjQ1MS0uNDIgMi4wODYtLjc5Ni0uMjQ2Ljc2Ny0uNzY2IDEuNDEtMS40NDMgMS44MTYuNjY0LS4wOCAxLjI5Ny0uMjU2IDEuODg1LS41MTctLjQzOS42NTYtLjk5NiAxLjIzNC0xLjYzOSAxLjY5N3oiLz48L3N2Zz4="><a target="_blank" href="https://twitter.com/ayush123460">@ayush123460</a></span>
      <span><img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0xOSAyNGgtMTRjLTIuNzYxIDAtNS0yLjIzOS01LTV2LTE0YzAtMi43NjEgMi4yMzktNSA1LTVoMTRjMi43NjIgMCA1IDIuMjM5IDUgNXYxNGMwIDIuNzYxLTIuMjM4IDUtNSA1em0tMy4yODgtNC44ODhsLS40MjQtMS40OCAxLjAyNC45NTIuOTY4Ljg5NiAxLjcyIDEuNTJ2LTE0LjM1MmMwLS45MTItLjczNi0xLjY0OC0xLjY0LTEuNjQ4aC0xMC43MmMtLjkwNCAwLTEuNjQuNzM2LTEuNjQgMS42NDh2MTAuODE2YzAgLjkxMi43MzYgMS42NDggMS42NCAxLjY0OGg5LjA3MnptLTEuNDQtMy42NjRjMS43NjgtLjA1NiAyLjQ0OC0xLjIxNiAyLjQ0OC0xLjIxNiAwLTIuNTc2LTEuMTUyLTQuNjY0LTEuMTUyLTQuNjY0LTEuMTUyLS44NjQtMi4yNDgtLjg0LTIuMjQ4LS44NGwtLjExMi4xMjhjMS4zNi40MTYgMS45OTIgMS4wMTYgMS45OTIgMS4wMTYtLjgzMi0uNDU2LTEuNjQ4LS42OC0yLjQwOC0uNzY4LS41NzYtLjA2NC0xLjEyOC0uMDQ4LTEuNjE2LjAxNmwtLjEzNi4wMTZjLS4yOC4wMjQtLjk2LjEyOC0xLjgxNi41MDRsLS40NzIuMjMycy42NjQtLjYzMiAyLjEwNC0xLjA0OGwtLjA4LS4wOTZzLTEuMDk2LS4wMjQtMi4yNDguODRjMCAwLTEuMTUyIDIuMDg4LTEuMTUyIDQuNjY0IDAgMCAuNjcyIDEuMTYgMi40NCAxLjIxNmwuNTM2LS42NjRjLTEuMDE2LS4zMDQtMS40LS45NDQtMS40LS45NDRsLjIyNC4xMzYuMDMyLjAyNC4wMzIuMDE4LjAwOS4wMDQuMDMxLjAxOGMuMi4xMTIuNC4yLjU4NC4yNzIuMzI4LjEyOC43Mi4yNTYgMS4xNzYuMzQ0LjYuMTEyIDEuMzA0LjE1MiAyLjA3Mi4wMDguMzc2LS4wNjQuNzYtLjE3NiAxLjE2LS4zNDQuMjgtLjEwNC41OTItLjI1Ni45Mi0uNDcyIDAgMC0uNC42NTYtMS40NDguOTUybC41MjguNjQ4em0tMy43Mi0zLjczNmMtLjQ1NiAwLS44MTYuNC0uODE2Ljg4OHMuMzY4Ljg4OC44MTYuODg4Yy40NTYgMCAuODE2LS40LjgxNi0uODg4LjAwOC0uNDg4LS4zNi0uODg4LS44MTYtLjg4OHptMi45MiAwYy0uNDU2IDAtLjgxNi40LS44MTYuODg4cy4zNjguODg4LjgxNi44ODhjLjQ1NiAwIC44MTYtLjQuODE2LS44ODhzLS4zNi0uODg4LS44MTYtLjg4OHoiLz48L3N2Zz4=">Ayush#4148</a></span>
    </div>
  </section>
</div>
</template>

<script>
import axios from 'axios'

export default {
  name: 'Home',
  data: () => {
    return {
      name: null,
      email: null,
      message: null
    }
  },
  methods: {
    submitForm() {
      event.preventDefault()
	  if(this.name == null || this.email == null || this.message == null)
		alert('Your name, email, or message cannot be empty.')
	  else {
    	  document.querySelector('input[type=text]').disabled = true
	      document.querySelector('input[type=email]').disabled = true
    	  document.querySelector('textarea').disabled = true
	      document.querySelector('input.btn').disabled = true

    	  axios.post('https://cms.aplesports.com/api/forms/submit/contact', {
	        form: {
    	      name: this.name,
	          email: this.email,
        	  message: this.message
    	    }
	      }, {
    	    headers: {
	          'Cockpit-Token': process.env.VUE_APP_CMS_TOKEN
        	}
    	  })
	      .then(() => {
        	alert('Your message has been submitted.')
      	})
	  }
    }
  }
}
</script>
