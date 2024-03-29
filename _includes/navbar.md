<!-- _includes/navbar.md -->

<style>
  .navbar {
    background-color: #3498db; /* Background color */
    padding: 15px 0; /* Padding around navbar links */
    text-align: center; /* Center align navbar links */
    font-family: Arial, sans-serif; /* Font family */
    border-bottom: 2px solid black;
    border-top: 2px solid black;
  }

  .navbar a {
    color: #fff; /* Text color */
    text-decoration: none; /* Remove underline from navbar links */
    padding: 10px 20px; /* Padding around navbar links */
    margin: 0 5px; /* Add margin to navbar links */
    font-weight: bold; /* Make the text bold */
    transition: background-color 0.3s ease; /* Smooth transition on hover */
    position: relative; /* Positioning context for the line */
    font-size: 14.5px;
  }
  .navbar1 {
    background-color: #3498db; /* Background color */
    padding: 15px 0; /* Padding around navbar links */
    text-align: left; /* Center align navbar links */
    font-family: Arial, sans-serif; /* Font family */
  }

  .navbar a:not(:last-child):after {
    content: ''; /* Empty content */
    position: absolute; /* Position the line absolutely */
    top: 50%; /* Align the line vertically */
    right: 0; /* Position the line to the right */
    transform: translateY(-50%); /* Center the line vertically */
    width: 1px; /* Line width */
    height: 80%; /* Line height */
    background-color: #fff; /* Line color */
  }

  .navbar a:hover {
    background-color: #2980b9; /* Background color on hover */
  }
</style>

<div class="navbar">
<div class="navbar1">
<a href="/">&nbsp;&nbsp;Home</a>
</div>
  <div>
  <a href="/architectural-styles">Architectural Styles</a>
  <a href="/cloud-native-attributes">Cloud Native Attributes</a>
  <a href="/design-principles">Design Principles</a>
  <a href="/design-patterns">Design Patterns</a>
  <a href="/security-design-patterns">Security Patterns</a>
  <a href="/architectural-patterns">Architectural Patterns</a>
  </div>
</div>
