# Build-a-Survey-Form
New Responsive Web Design freeCodeCamp
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Build a Survey Form</title>
    <link rel="stylesheet" href="styles.css" type="text/css">
  </head>
  <body>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description">Thank you for taking the time to help us improve the platform</p>
    <form id="survey-form">
      <label for="name" id="name-label">Name</label>
      <input type="text" id="name" required placeholder="Enter Your Name">
      <hr>
      <label for="email" id="email-label">Email</label>
      <input type="email" id="email"  placeholder="Enter Your Email" required>
      <hr>
      <label for="number" id="number-label">Age <span>(optional)</span></label>
      <input type="number" id="number" placeholder="Age" min="1" max="100">
      <label>Which option best describes your current role?</label>
      <hr>
            <select name="current-role" id="dropdown">
        <option value="select-current-role" disabled selected>Select Current Role</option>
        <option value="student">Student</option>
        <option value="full-time-job">Full Time Job</option>
        <option value="full-time-learner">Full Time Learner</option>
        <option value="prefer-not-to-say">Prefer not to say</option>
        <option value="other">Other</option>
        <section class="rec">
          <p>Would you recommend freeCodeCamp to a friend?</p>
          <label>Definitely</label>
          <input type="radio" value="definitely" name="definitely">
          <label>Maybe</label>
          <input type="radio" value="maybe" name="maybe">
          <label>Not sure</label>
          <input type="radio" value="not-sure" name="not-sure">
        </section>
        <label for="dropdown">What is your favorite feature of freeCodeCamp?</label>
             <select name="current-role" id="dropdown">
        <option value="select-current-role" disabled selected>Select an option</option>
        <option value="cheallenges">Challenges</option>
        <option value="projects">Projects</option>
        <option value="community">Community</option>
        <option value="open-source">Open Source</option>
      </select>
      <section>
        <p>What would you like to see improved? <span class="text">(Check all that apply)</span></p>
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
        <label></label>
        <input type="checkbox" value="improved">
      </section>
    </form>
  </body>
</html>
