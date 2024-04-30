---
layout: default
title: Design Patterns
permalink: /design-patterns
---

<style>
  .button-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    justify-items: center;
    align-items: center;
    gap: 20px;
  }

  .button a {
    text-decoration: none;
  }
  .button {
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

  .box {
    border: 3px solid #ccc;
    padding: 10px;
    border-radius: 5px;
    width: 200px; /* Adjust as needed */
    text-align: center;
  }
</style>

<div class="button-container">
  <div class="button">
    <div class="box">
      <a href="/design-pattern/rate-limitor">
        <img src="../pictures/rate-limitor-icon.png" alt="Rate Limiter">
        <h3>Rate Limiter</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/observer">
        <img src="../pictures/observericon.png" alt="Observer">
        <h3>Observer</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/circuit-breaker">
        <img src="../pictures/circuit-breakericon.png" alt="Circuit Breaker">
        <h3>Circuit Breaker</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/retry">
        <img src="../pictures/retryicon.png" alt="Retry">
        <h3>Retry</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/ambassador">
        <img src="../pictures/ambassadoricon.png" alt="Ambassador">
        <h3>Ambassador</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/bulkhead">
        <img src="../pictures/bulkheadicon.png" alt="Bulkhead">
        <h3>Bulkhead</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href=" /design-pattern/load-balancer">
        <img src="../pictures/loadbalancericon.png" alt="Load Balancer">
        <h3>Load Balancer</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/queue-based-load-leveling">
        <img src="../pictures/queue-basedicon.png" alt="Queue Based Load Leveling">
        <h3>Queue Based Load Leveling</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/sidecar-pattern">
        <img src="../pictures/sidecaricon.png" alt="Sidecar">
        <h3>Sidecar</h3>
      </a>
    </div>
  </div>
  <div class="button">
    <div class="box">
      <a href="/design-patterns/throttling">
        <img src="../pictures/throttlingicon.png" alt="Throttling">
        <h3>Throttling</h3>
      </a>
    </div>
  </div>
</div>
