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
      <label for="name-label" id="name-label">
      <legend>Name</legend>
      <input id="name" placeholder="Enter your name" type="text" required>
      </label>
      <label for="email-label" id="email-label">
      <legend>Email</legend>
      <input id="email" placeholder="Enter your Email" type="email" required>
      </label>
      <label for="number-label" id="number-label">
      <legend>Age (optional)</legend>
      <input id="number" type="number" placeholder="Age" min="1" max="120">
      </label>
      <br>
      <label for="dropdown">Which option best describes your current role?</label>
      <br>
      <select name="dropdown" id="dropdown">
        <option value="student">Student</option>
        <option value="full-time-job">Full Time Job</option>
        <option value="full-time-learner">Full Time Learner</option>
        <option value="prefer-not-to say">Prefer not to say</option>
        <option value="other">Other</option>
      </select>
      <legend>Would you recommend freeCodeCamp to a friend?</legend>
      <label for="definitely">
        <input id="definitely" type="radio" name="definitely-maybe--not-sure" value="definitely">Definitely
      </label>
      <br>
      <label for="maybe">
        <input id="maybe" type="radio" name="definitely-maybe--not-sure" value="maybe">Maybe
      </label>
      <br>
      <label for="not-sure">
        <input id="not-sure" type="radio" name="definitely-maybe--not-sure" value="not-sure">Not sure
      </label>
      <legend>What is your favorite feature of freeCodeCamp?</legend>
      <select name="dropdown" id="dropdown">
      <option value="challenges">Challenges</option>
      <option value="projects">Projects</option>
      <option value="community">Community</option>
      <option value="open-source">Open Source</option>
      </select>
    </form>
  </body>
</html>
