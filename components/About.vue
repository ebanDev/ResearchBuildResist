<template>
  <section id="about">
    <h1>Hi there, I’m <span>Eban</span> !</h1>
    <h2>Welcome to my corner of the internet 🌱</h2>
    <p>i’m a student building in the realms of sysadmin, web development, and cybersecurity to catalyze radical
      change</p>
  </section>
</template>

<style lang="scss" scoped>
@import "/assets/scss/variables.scss";

section {
  padding-top: 300px;
}

p {
  margin-top: 50px !important;
  line-height: 1.5;
}

@media (max-width: 768px) {
  section {
    padding-top: 150px;
  }
}
</style>