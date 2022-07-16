# Build-a-Survey-Form
New Responsive Web Design freeCodeCamp
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Build a Survey Form</title>
    <link rel="stylesheet" href="./styles.css" type="text/css">
  </head>
  <body>
    <div class="container">
      <header class="header">
        <h1 id="title" class="text-center">freeCodeCamp Survey Form</h1>
        <p id="description" class="description text-center">
          Thank you for taking the time to help us improve the platform
        </p>
      </header>
      <form id="survey-form">
        <div class="form-group">
          <label for="name" id="name-label">Name</label>
          <input type="text" id="name" placeholder="Enter Your Name" required>
        </div>
        <div class="form-group">
          <label for="email" id="email-label">Email</label>
          <input type="email" id="email"  placeholder="Enter Your Email" required>
        </div>
        <div class="form-group">
          <label for="number" id="number-label">Age <span>(optional)</span></label>
          <input type="number" id="number" placeholder="Age" min="1" max="100" required>
        </div>
        <div class="form-group">
        <p for="dropdown">Which option best describes your current role?</p>
          <select id="dropdown" name="current-role" class="form-control" required>
            <option disabled selected>Select Current Role</option>
            <option value="student">Student</option>
            <option value="full-time-job">Full Time Job</option>
            <option value="full-time-learner">Full Time Learner</option>
            <option value="prefer-not-to-say">Prefer not to say</option>
            <option value="other">Other</option<
          </select>
        </div>
     <div class="form-group">
       <p>Would you recommend freeCodeCamp to a friend?</p>
         <label>
           <input name="user-recommend" value="definitely" type="radio" class="input-radio" checked/>Definitely
         </label>
         <label>
           <input name="user-recommend" value="maybe" type="radio" class="input-radio" checked/>Maybe
         </label>
         <label>
           <input name="user-recommend" value="not-sure" type="radio" class="input-radio" checked/>Not Sure
         </label>
    </div>
    <div class="form-group">
      <p>What is your favorite feature of freeCodeCamp?</p>
      <select  id="dropdown" name="current-role" class="form-control" required>
        <option disabled selected>Select an option</option>
        <option value="challenges">Challenges</option>
        <option value="projects">Projects</option>
        <option value="community">Community</option>
        <option value="open-source">Open Source</option>
      </select>
    </div>
    <div class="form-group">
      <p>
       What would you like to see improved? 
        <span class="text">(Check all that apply)</span>
      </p>
      <label
      ><input 
        name="prefer" 
        value="front-end-projects"
        type="checkbox"
        class="input-checkbox"
      />Front-end Projects</label>

      <label
      ><input 
        name="prefer"
        value="back-end-projects"
        type="checkbox"
        class="input-checkbox"
      />Back-end Projects</label>

     <label
     ><input 
       name="prefer"
       value="data-visualization"
       type="checkbox"
       class="input-checkbox"
     />Data Visualization</label>

     <label
     ><input 
       name="prefer"
       value="challenges"
       type="checkbox"
       class="input-checkbox"
     />Challenges</label>

     <label
     ><input 
       name="prefer"
       value="open-source-community"
       type="checkbox"
       class="input-checkbox"
     />Open Source Community</label>

     <label
     ><input 
       name="prefer"
       value="gitter-help-rooms"
       type="checkbox"
       class="input-checkbox"
     />Gitter Help Rooms</label>

     <label
     ><input 
       name="prefer"
       value="videos"
       type="checkbox"
       class="input-checkbox"
     />Videos</label>

     <label
     ><input 
       name="prefer"
       value="city-meetups"
       type="checkbox"
       class="input-checkbox"
     />City meetups</label>

     <label
     ><input 
       name="prefer"
       value="wiki"
       type="checkbox"
       class="input-checkbox"
     />Wiki</label>

     <label
     ><input 
       name="prefer"
       value="forum"
       type="checkbox"
       class="input-checkbox"
     />Forum</label>

     <label
     ><input 
       name="prefer"
       value="additional-courses"
       type="checkbox"
       class="input-checkbox"
     />Additional courses</label>
 
      </div>

      <div class="form-group">
        <p>Any comments or suggestions?</p>
        <textarea
        id="comments"
        class="input-text-area"
        name="comment"
        placeholder="Enter your comment here..."
        ></textarea>
      </div>

          <div class="form-group">
            <button type="submit" id="submit" class="submit-button">
              Submit
            </button>
          </div>
        </form>
      </div>
    </body>
  </html>
