---
layout: default
title: Architectural Styles
permalink: /architectural-styles
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
    text-decoration: none;
  }
  
  .box {
    border: 3px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    width: 200px;
    text-align: center;
  }

  .box img {
    width: 150px;
    height: auto;
  }

  .box h3 {
    margin-top: 10px;
    font-size: 18px;
  }
</style>

<div class="button-container">
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/monolith">
        <img src="{{ jekyll.baseurl }}/pictures/monolithicarchitecture.jpg" alt="Monolith">
        <h3>Monolithic Architecture</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/client-server">
        <img src="/pictures/Client-server-icon.jpg" alt="Client/Server">
        <h3>Client/Server</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/component-Based">
        <img src="/pictures/component based.jpg" alt="Component Based">
        <h3>Component Based</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/microservices.html">
        <img src="/pictures/Microservices.png" alt="Microservices">
        <h3>Microservices</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/microkernel">
        <img src="/pictures/Microkernel Architecture.jpg" alt="Microkernel Architecture">
        <h3>Microkernel Architecture</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/Event-Driven">
        <img src="/pictures/Event Driven-Icon.jpg" alt="Event Driven">
        <h3>Event Driven</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/Pipe&Filter">
        <img src="/pictures/Pipe & Filter.jpg" alt="Pipe & Filter">
        <h3>Pipe & Filter</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/layered">
        <img src="/pictures/LayerdIcon.png" alt="Layered">
        <h3>Layered</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-patterns/strangler">
        <img src="/pictures/StranglerIcon.png" alt="Strangler">
        <h3>Strangler</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-patterns/web3">
        <img src="/pictures/web3.png" alt="Web3">
        <h3>Web3</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-styles/low-code">
        <img src="/pictures/lowcodeicon.png" alt="Low Code">
        <h3>Low Code</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/architectural-patterns/screaming-architecture">
        <img src="/pictures/Screaming architecture.png" alt="Screaming Architecture">
        <h3>Screaming Architecture</h3>
      </a>
    </div>
  </div>
</div>
