<template>
  <div class="price-block">
    <h1>Pricing</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit.<br />
      Harum nobis reprehenderit ipsum reiciendis.
    </p>
    <div class="btn-block">
      <button
        @click="
          {
          }
        "
        class="btn btn-month"
      >
        Monthly
      </button>
      <button
        @click="
          {
          }
        "
        class="btn btn-year"
      >
        Yearly
      </button>
    </div>
  </div>
</template>
<style scoped>
.price-block {
  text-align: center;
  color: #fff;
}
.price-block h1 {
  font-size: 36px;
}
.btn-block {
  border: 2px solid #fff;
  border-radius: 6px;
  display: inline-block;
}
.btn-block .btn {
  width: 82px;
  cursor: pointer;
  border: 0;
  font-weight: bold;
  padding: 7px 16px;
  cursor: block;
}
.btn.btn-month {
  background: transparent;
  color: #fff;
}
.btn.btn-month:hover {
  background: #fff;
  color: #000;
}
.btn.btn-year:hover {
  background: transparent;
  color: #fff;
}
</style>
