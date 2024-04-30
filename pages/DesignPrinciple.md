---
layout: default
title: Design Principle
permalink: /design-principles
---

<style>
  .button-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    justify-items: center;
    padding-bottom: 50px;
    align-items: center; /* Align items vertically */
  }

  .button {
    text-align: center;
  }

  .box {
    border: 3px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    width: 200px; /* Adjust as needed */
    text-align: center;
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
      <a href="/design-principles/composable">
        <img src="./pictures/composable.png" alt="Composable">
        <h3>Composable</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/DRY">
        <img src="./pictures/DRY.png" alt="DRY">
        <h3>DRY(Don't Repeat Yourself)</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/KISS">
        <img src="./pictures/kiss.png" alt="KISS">
        <h3>KISS(Keep It Simple, Stupid)</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/hollywood">
        <img src="./pictures/hollywoodicon.png" alt="Hollywood">
        <h3>HOLLYWOOD</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/YAGNI">
        <img src="./pictures/yagniicon.png" alt="YAGNI">
        <h3>YAGNI</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/SOLID">
        <img src="./pictures/solidicon.png" alt="SOLID">
        <h3>SOLID</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/green-coding-principles">
        <img src="./pictures/greencodingicon.png" alt="Green Coding Principles">
        <h3>GREEN CODING</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/green-coding">
        <img src="./pictures/green3.png" alt="Green Coding (3 Pillars and Benefits)">
        <h3>Green Coding (3 Pillars and Benefits)</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-principles/green-coding-tangible">
        <img src="./pictures/greentabgible.png" alt="Green Coding (Tangible Things to Do)">
        <h3>GREEN CODING(TANGIBLE THINGS TO DO)</h3>
      </a>
    </div>
  </div>
  <!-- Add more buttons similarly -->
</div>
