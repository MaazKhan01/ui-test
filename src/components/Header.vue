<template>
    <div class="header">
      <div class="container d-flex">
        <div><h1>avacado</h1></div>
        <div class="nav-links">
          <ul class="d-flex">
            <li>
              <a href="#" target="_blank">Product</a>
            </li>
            <li><a href="#" target="_blank">Solution</a></li>
            <li><a href="#" target="_blank">Blog</a></li>
            <li><a href="#" target="_blank">Download</a></li>
            <li><a href="#" target="_blank">Pricing</a></li>
          </ul>
        </div>
        <div class="auth-btns">
          <button
            @click="
              {
              }
            "
            class="btn-login btn"
          >
            Login
          </button>
          <button
            @click="
              {
              }
            "
            class="btn-signup btn"
          >
            Signup
          </button>
        </div>
      </div>
    </div>
  </template>
  <style scoped>
  .header {
  
    color: #fff;
  }
  .header .container {
    justify-content: space-between;
  }
  .nav-links {
    justify-content: space-around;
  }
  .nav-links ul {
    width: 350px;
    justify-content: space-around;
  }
  .nav-links ul li {
    list-style: none !important;
  }
  .btn {
    width: 80px;
    padding: 7px 12px;
    border-radius: 6px;
    outline: none;
    cursor: pointer;
    border: 0;
    font-weight: bold;
    margin: 0 5px;
  }
  .btn-signup {
    background: #479147;
    color: #fff !important;
  }
  a {
    text-decoration: none;
    font-weight: bold;
    color: #fff !important;
  }
  </style>
  