<template>


    <div>
      <div class="d-flex nav-top align-items-center logo px-5">
        <div class="me-auto p-2">
          <h3 id="welcome">Welcome</h3>
        </div>
        <div class="p-4 nav-item d-flex flex">

          <nuxt-link class="nav-link mx-2" to="/admin/about">Admin</nuxt-link>
          <nuxt-link class="nav-link" to="/login">Login</nuxt-link>
        </div>
    </div>

    <section id="profile" class="justify-content-center text-center bg-gradient bg-secondary-subtle mx-5 p-4 mb-3">
        <div class="profile ">
          <img class="rounded-circle"
            src="../public/niko.jpg"
            alt="nikosprofile"
            height="150px"
            width="150px"
          />
          <h2 id="#nama-niko">Niko Aji Nugroho</h2>
          <h4>Front-End Developer</h4>
          <div class="nav-item d-flex justify-content-center">
            <a class="nav-link" href="https://github.com/nicorporate">Github |</a>
            <a class="nav-link" href="https://id.linkedin.com/in/nikonugroho">| Linkedin</a>
          </div>

        </div>
    </section>

    <div id="cards" class="row row-cols-md-2 g-4 bg-white mx-5 pb-3">
        <div class="left-content p-3 mr-3 ">
            <div class="left-content-1 card p-4 mx-3">
                <h4 class="sub">About Me</h4>
                <p class="text-">
                I'm a fresh graduate of Computer Engineering at Brawijaya University.
                Experienced in concepting, planning, managing, and executing events,
                moreover capable of being a speaker in it. I also skilled in
                programming (C/C++, Python, HTML, CSS, PHP, and MySQL) based on
                completing some projects in the college back then. In order to channel
                my hobby, sometimes I make music for personal or professional purpose
                using FL Studio. I have a strong enthusiasm to learn something
                challenging and able to adapt in any condition.
                </p>
                <button class="btn btn-primary" @click="toAbout">Update</button>
            </div>
            <br>

          <div class="left-content-2 card p-4 mx-3">
            <h4>Education</h4>
            <p>University of Brawijaya</p>
            <p>Bachelor of Engineering - BE, Computer Engineering</p>
            <p>Aug 2019 - Jul 2023</p>
            <button class="btn btn-primary" @click="toEducation">Update</button>
          </div>

        </div>
        <div class="right-content col p-3">
          <div class="right-content-1 card p-5 mx-3">
            <h4>Work Experience</h4>
            <ul>
              <li>
                BTJ Academy Trainee Batch 1 at Bangunindo Teknusa Jaya (Nov
                2023-present)
              </li>
              <li>
                Vice Executive at HIMATEKKOM UB (Feb 2022-Jan 2023)
              </li>
              <li>Website Developer at KPKNL Malang (Aug 2022-Nov 2022)</li>
            </ul>
            <button class="btn btn-primary" @click="toWork">Update</button>
          </div>
          <br>
            <div id="motto" class="card text-center p-5 mx-3 form-control-lg">
              <em>Motto: "Di dunia ini, hanya Aji yang tidak memiliki motto"</em>
              <button class="btn btn-primary" @click="toMotto">Update</button>
            </div>
          </div>
        </div>
    </div>

    <footer class="card-footer text-body-secondary text-center pt-3 pb-3 ">&copy; 2023 Landing Page</footer>

</template>

<script>
export default {
    methods: {
        toLogin(){
            alert("Login First!")
            navigateTo('/login')
        },
        toAbout(){
            navigateTo('/admin/about')
        },
           toEducation(){
            navigateTo('/admin/education')
        },
           toWork(){
            navigateTo('/admin/work')
        },
           toMotto(){
            navigateTo('/admin/motto')
        },
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat');



.nav-link{
    color: rgb(62, 62, 244) !important;
}

.nav-link:hover {
    color: var(--main-text-color) !important;
    transition: color 0.5s ease;
}



.btn-primary {
    background-color: rgb(62, 62, 244) !important;

}

.btn-primary:hover {
    background-color: rgb(152, 152, 255) !important;
    color: white;
    transition: background-color 0.5s ease;
}

.btnsubmit {
    width: 100%;
}

footer{
  background-color: rgb(187, 188, 189)  !important;
}

.nav-top{
  background-color:  rgb(207, 209, 211);
}

#welcome{
  color: rgb(62, 62, 244) ;
}

</style>