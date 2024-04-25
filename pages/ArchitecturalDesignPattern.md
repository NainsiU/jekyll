---
layout: default
title: Architectural Design Patterns
permalink: /architectural-patterns
---
<style>
  .button-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    justify-items: center;
    padding-bottom: 50px;
  }

  .button {
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

  .button h3 {
    margin-top: 10px;
  }

  .box {
    border: 3px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    width: 200px; /* Adjust as needed */
    text-align: center;
  }

  .button a {
    text-decoration: none;
  }

  h1 {
    font-size: 36px; /* Increase font size */
    text-align: left; /* Center align the text */
    margin-top: 40px; /* Add some top margin */
  }
</style>

<div class="button-container">
  <div class="button">
    <div class="box">
      <a href="/architectural-pattern/model-view-controller">
        <img src="../pictures/mvcicon.png" alt="MVC">
        <h3>Model View Controller(MVC)</h3>
      </a>
    </div>
  </div>
    <div class="button">
    <div class="box">
      <a href="/architectural-pattern/domain-driven-design">
        <img src="../pictures/dddicon.png" alt="DDD">
        <h3>Domain Driven Design(DDD)</h3>
        &nbsp;
        </a>
    </div>
  </div>
    <div class="button">
    <div class="box">
      <a href="/architectural-pattern/hexagonal-architecture">
        <img src="../pictures/hexaicon.png" alt="Hexagonal">
        <h3>Hexagonal</h3>
      </a>
    </div>
  </div>

  <div class="button">
    <div class="box">
      <a href="/architectural-pattern/mvp">
        <img src="../pictures/mvpicon.png" alt="MVP">
        <h3>MVP (Model View Presenter)</h3>
        &nbsp;
      </a>
    </div>
  </div>

  <div class="button">
    <div class="box">
      <a href="/architectural-pattern/static-content-hosting">
        <img src="../pictures/SCH.png" alt="SCH">
        <h3>Static Content Hosting</h3>
        &nbsp;
      </a>
    </div>
  </div>

 <div class="button">
    <div class="box">
      <a href="/architectural-patterns/backend-for-frontend">
        <img src="../pictures/bfficon.png" alt="SCH">
        <h3>Backend For Frontend(BFF)</h3>
        &nbsp;
      </a>
    </div>
  </div>



  <!-- Add more buttons similarly -->
</div>
