<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container-one">
        <div class="profile">
          <img src="../assets/github-icon.svg" alt="" />
          <h3>Matias Coronel</h3>
          <p>FullStack Developer</p>
        </div>
        <div class="social-links">
          <div class="link">
            <a href="">
              <img src="../assets/github-icon.svg" alt="" />
              <h2>GitHub</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/linkedin-icon.svg" alt="" />
              <h2>LinkedIn</h2>
            </a>
          </div>
        </div>
      </div>
      <div class="container-two">
        <div class="about-me">
          <h1>About me</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, ipsa
            quia eaque maiores deleniti consectetur vitae error voluptate
            eveniet, vero iusto, labore consequatur placeat ab modi repudiandae
            sunt fugit libero?
          </p>
        </div>
        <div class="technology-section">
          <h1>Technologies Studied</h1>
          <div class="logos">
            <img src="../assets/html-icon.svg" alt="" />
            <img src="../assets/javascript-icon.svg" alt="" />
            <img src="../assets/css-icon.svg" alt="" />
            <img src="../assets/react-icon.svg" alt="" />
            <img src="../assets/mongodb-icon.svg" alt="" />
            <img src="../assets/express-icon.svg" alt="" />
          </div>
        </div>
        <div class="button-container">
          <div class="projects-button">
            <a href="">My Projects</a>
          </div>
          <div class="projects-button">
            <a href="">My Resume</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
  padding-top: 40px;
}

img {
  height: 40px;
}
.main-container {
  display: flex;
  flex-direction: row;
  background-color: #a87bc7;
  border-radius: 25px;
  width: 60%;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.container-one {
  background-color: #734a91;
  padding: 2.5%;
  width: 30%;
  border-radius: 25px;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.profile img {
  height: 5rem;
  border-radius: 50%;
}

.link a {
  text-decoration: none;
  color: #2c3e50;
  font-size: 10px;
}

.link img {
  height: 2rem;
}

.container-two {
  margin: 2.5%;
  width: 70%;
}

.about-me {
  text-align: left;
}

.logos img {
  height: 2.5rem;
}

.button-container {
  margin-top: 5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.projects-button {
  background-color: #734a91;
  border-radius: 15px;
  padding: 5px;
  margin: 5px;
}

.projects-button a {
  text-decoration: none;
  color: #fff;
}

@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}
</style>
