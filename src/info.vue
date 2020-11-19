<template>
  <div id="info">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <div class="main-container">
      <img src="./assets/web layout-02.png" />
    </div>

    <b-col>
      <div class="title">
        <h2>INTRODUCTION</h2>
      </div>

      <div class="square"></div>

      <div class="button">
        <input type="submit" value="BACK" />
      </div>

      <div>
        <h2 class="body">
          The coronavirus COVID-19 pandemic is the defining global <br />
          health crisis of our time and the greatest challenge. But, there is
          <br />
          someone that sacrifices, risking their lives to fight against the
          <br />
          virus, which is the frontliners. Their existence have saved <br />
          countless lives and made thousands of difference, they also <br />
          sacrificed for the benefit of the nation.This is a website to convey
          <br />
          our appreciation to the COVID-19 hero, which is the frontliners.
          <br />
          We can send our appreciation via our mobile, and the message <br />
          will be reflected in the website. The message that is sent by the
          <br />
          audience will then uncover each of the roles of the frontliners.
        </h2>
      </div>
    </b-col>
  </div>
</template>


<script>
export default {
  name: "info",
  components: {},
  data() {
    return {};
  },
  methods: {},
  computed: {},
};
</script>

<style>
#app {
  font-family: "Montserrat";
}

.main-container {
  position: fixed;
}

.body {
  font-size: 20px;
  font-weight: normal;
  margin-top: -435px;
  margin-left: 410px;
  color: #00ffd4;
  line-height: 30px;
}

.title {
  color: #00ffd4;
  padding-top: 135px;
  padding-left: 600px;
}

.square {
  height: 350px;
  width: 700px;
  background-color: #ffffff00;
  border-color: #00ffd4;
  border-radius: 14px;
  border-style: solid;
  margin-top: 30px;
  margin-left: 380px;
}

input[type="SUBMIT"] {
  width: 100%;
  padding: 10px 20px;
  margin: 30px 380px;
  border: none;
  border-radius: 14px;
  cursor: pointer;
  border-color: #00ffd4;
  border-style: solid;
  width: 280px;
  background-color: #ffffff00;
}

input[type="submit"]:hover {
  background-color: #00ffd4;
  color: #000000;
}

input[type="submit"] {
  background-color: #ffffff00;
  color: #00ffd4;
  font-weight: bold;
  width: 700px;
}
</style>