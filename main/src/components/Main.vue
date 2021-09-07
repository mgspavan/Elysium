<template>
  <div align="center">
    <div class="wrapper">
      <h1>Something Awesome Is Coming<span class="dot">!</span></h1>
      <div class="img">
        <img class="img" src="../assets/Elysium.svg" alt="logo" />
      </div>

      <div class="icons">
        <a
          class="a"
          href="https://instagram.com/interiorsbyelysium?utm_medium=copy_link"
          ><i class="fab fa-instagram"></i
        ></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style>
body {
  background: #fff2e8;
  color: #d5b36b;
}
.wrapper {
  position: absolute;
  left: 22%;
  top: 10%;
}

h1 {
  font-size: 50px;
  text-align: center;

  font-family: "Georgia, 'Times New Roman', Times, serif";
  margin-bottom: 0;
  line-height: 1;
  font-weight: 700;
}
.img {
  display: flex;
  justify-content: center;
  width: 70%;
  margin-top: 7%;
}

.icons {
  text-align: center;
  font-size: 50px;
  margin: 50px;
}

.a {
  color: black;
}
.a:hover {
  color: #d5b36b;
}

@media screen and (max-width: 570px) {
  .wrapper {
    position: absolute;
    left: 0%;
    top: 10%;
  }
  h1 {
    font-size: 40px;
    width: 90%;

    font-family: "Poppins", sans-serif;
    margin-bottom: 0;
    line-height: 1;
    font-weight: 700;
  }
  .icons {
    text-align: center;
    font-size: 40px;
    margin: 50px;
    color: black;
  }
  .icons:hover {
    color: #d5b36b;
  }
}
</style>
