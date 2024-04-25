---
layout: default
title: Design Principles
permalink: /design-principles
---



<style>
  .button-container {
    display: flex;
    justify-content: center;
    align-items: center;
     padding-bottom: 50px;
  }

  .button {
    margin: 10px;
    text-align: center;
    border: 4px solid #ccc;
    padding: 10px;
    border-radius: 5px;
  }

  .button img {
    width: 150px; /* Adjust as needed */
    height: auto;
    display: block;
    margin: 0 auto;
  }

  .button a {
    text-decoration: none;
  }
  
  .button h3 {
    margin-top: 10px;
    color: dark blue;
     
  }

  .box {
    border: 3px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    width: 200px; /* Adjust as needed */
    text-align: center;
  }
   h1 {
      font-size: 36px; /* Increase font size */
      text-align: left; /* Center align the text */
      margin-top: 40px; /* Add some top margin */
    }
</style>

<!-- <h1>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Design Principles</h1> -->
<div class="button-container">
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/monolith/">
        <img src="/pictures/monolithicarchitecture.jpg" alt="Picture 1">
        <h3>Clean code</h3>
      </a>
    </div>
  </div>
    <div class="button">
    <div class="box">
      <a href="/architectural-styles/client-server">
        <img src="/pictures/monolithicarchitecture.jpg" alt="Picture 1">
        <h3>Composable</h3>
        &nbsp;  
      </a>
    </div>
  </div>
    <div class="button">
    <div class="box">
      <a href="/page1.html">
        <img src="/pictures/monolithicarchitecture.jpg" alt="Picture 1">
        <h3>DRY(Don't Repeat Yourself)</h3>
      </a>
    </div>
  </div>

  <div class="button">
    <div class="box">
      <a href="/page1.html">
        <img src="/pictures/monolithicarchitecture.jpg" alt="Picture 1">
        <h3>KISS(Keep It Simple, Stupid)</h3>
        &nbsp;
      </a>
    </div>
  </div>

  <!-- Add more buttons similarly -->
</div>

