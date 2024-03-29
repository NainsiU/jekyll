---
---

{% include navbar.md %}

<style>
  body {
    background-color: #f5f5f5; /* Very light background color */
    font-family: Arial, sans-serif;
  }

  .container {
    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
  }

  .title {
    font-size: 40px;
    margin-bottom: 20px;
    color: #333;
  }

  .main-image {
    width: 100%;
    max-width: 800px;
    height: auto;
    margin-bottom: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
    padding-top: 40px;
  }

  .image-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .image-box {
    width: calc(33.33% - 20px); /* Adjust as needed */
    margin: 10px;
    padding: 20px;
    border: 1px solid #ccc;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
  }

  .image-box h3 {
    margin-top: 0;
    color: #333;
  }

  .image-box a {
    text-decoration: none;
    color: #333;
  }

  .image-box:hover {
    transform: translateY(-5px);
    transition: transform 0.3s ease;
     background-color: #eaf2f8;
  }
</style>

<div class="container">
  <!--<h1 class="title">Architectural Styles</h1>-->
  

  <div class="image-container">
    <div class="image-box">
      <a href="/architectural-styles">
        <h3>Architectural Styles</h3>
      </a>
    </div>
    <div class="image-box">
      <a href="/cloud-native-attributes">
        <h3>Cloud Native Attributes</h3>
      </a>
    </div>
    <div class="image-box">
      <a href="/design-principles">
        <h3>Design Principles</h3>
      </a>
    </div>
    <div class="image-box">
      <a href="/design-patterns">
        <h3>Design Patterns</h3>
      </a>
    </div>
    <div class="image-box">
      <a href="/security-design-patterns">
        <h3>Security Design Patterns</h3>
      </a>
    </div>
    <div class="image-box">
      <a href="/architectural-patterns">
        <h3>Architectural Patterns</h3>
      </a>
    </div>
  </div>
  
  <img class="main-image" src="/pictures/designpattern.jpg" alt="Main Image">

 

</div>
 {% include footer.md %}