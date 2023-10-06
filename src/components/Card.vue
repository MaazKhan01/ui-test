<template>
  <div class="card-body">
    <div class="card" v-for="cardData in priceCard" :key="cardData.price">
      <!-- <ul>
    
    <li>{{ cardData.name }}</li>
    </ul> -->
      <h3>{{ cardData.name }}</h3>
      <p>{{ cardData.about }}</p>
      <div>
        <h4>${{ cardData.price }} <span>/ month</span></h4>
        <strong>One user only</strong>
        <button class="btn-trial" v-bind:class="cardData.class">
          Start Free Trial
        </button>
      </div>
      <ul>
        <li>Unlimit project</li>
        <li>Fully-featued inspect</li>
        <li>File management</li>
        <li>Public share</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      priceCard: [
        {
          name: "Solo",
          price: "15",
          about: "Provident impedit in suscipit facilis odio maxime nostrum.",
          class: "btn-trial-month",
        },
        {
          name: "Team",
          price: "25",
          about: "Lorem ipsum dolor sit amet consectetur, adipisicing elit.",
        },
      ],
    };
  },

  methods: {},
  mounted() {},
};
</script>
<style scoped>
.card-body {
  display: flex;
  width: 550px;
  position: absolute;
  margin: 6px;
  top: -70px;
  /* flex-wrap: wrap; */
}
.card::before {
  content: "";
  background-image: url("/card-img.png");
  background-size: 45px 45px;
    display: inline-block;
    width: 45px;
    background-repeat: no-repeat;
    height: 45px;
    position: absolute;
    left: 0;
    right: 0;
    margin: auto;
    margin-top: -40px;
}
.card {
  margin: 0px 10px;
  background: #fff;
  border: 1px solid #eee;
  padding: 15px;
  border-radius: 16px;
  position: relative;
}
.card p {
  max-width: 230px;
}
.btn-trial {
  background: orange;
  color: #fff;
  cursor: pointer;
  border-radius: 6px;
  padding: 10px 14px;
  border: none;
  width: 100%;
  display: block;
  margin: 8px 0px;
}
.card ul {
  padding: 0;
}
.card h4 {
  font-size: 30px;
  font-weight: bold;
}
.card h4 > span {
  color: #b6b6b6;
  font-size: 14px;
}
.card li {
  list-style: none;
  margin: 8px 0px;
  font-size: 14px;
  /* font-weight: bold; */
}
</style>
