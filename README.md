# Build-a-Survey-Form
Responsive Web Design freeCodeCamp
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Survey Form freeCodeCamp</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description">Thank you for taking the time to help us improve the platform</p>
    <form id="survey-form"> 
      <label for="name">
      <legend>Name</legend>
      <input id="name" placeholder="Enter your name" type="text" required>
      </label>
      <label for="email">
      <legend>Email</legend>
      <input id="email" placeholder="Enter your Email" type="text" required>
      </label>
      <label for="number">
      <legend>Age (optional)</legend>
      <input id="number" type="number" placeholder="Age" min="1" max="120">
      </label> 
      <label>
        <legend>Which option best describes your current role?</legend>
        <input select="dropdown" placeholder="Selct current role">
      </label>
    </form>
  </body>
</html>
