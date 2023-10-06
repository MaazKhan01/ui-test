<template>
  <div class="footer-main">
    <h5>Compare Planes and Features</h5>
    <div class="d-flex footer container">
      <div class="footer-left">
        <h3>
          Avocode is Helping over 10,000 Forward-Thinking Teams Create Great
          Digital Products.
        </h3>
      </div>
      <div class="footer-right">
        <div>
          "Avocode is simplythe best handoff software in the space. It was one
          of the best investment we made."
        </div>
        <div class="d-flex">
          <span class="avatar"><img src="/avatar.jpg" alt="avatar" width="50px"/> </span>
          <div class="bio">John Doe <span>Founder & CEO</span></div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.footer {
    background: #eee;
    margin: auto;
    padding: 25px;
    justify-content: space-between;
    flex-wrap: wrap;
    border-radius: 5px;
margin: auto;
}
.footer-right {
    width: 50%;
    display: flex;
    flex-direction: column;
    height: 190px;
    justify-content: space-around;
    margin: 22px 0px 0 0 ;
}
.footer-left {
    width: 50%;
}
.avatar img{
    margin-right: 6px;
    border-radius: 50px;
}
.footer-main {
    margin: 20px 0px;
}
.footer h3 {
    padding: 70px;
padding-top: 30px;
    font-weight: 900;
}
.bio {
    display: flex;
    font-size: 14px;
    flex-direction: column;
}
h5 {
    text-align: center;
}
</style>
