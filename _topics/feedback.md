---
layout: default
type: card
formsum: 
sortorder: 1.0
appsused: 
title: "Anonymous Student Feedback"
level: 
brightspace: 
links: 
video: 
downloads: 
description: "This form offers you an opportunity to tell me if we can improve anything in your Computer Graphics courses. Rest assured that the submissions are anonymous in an effort to encourage complete openness."
details: |
  <div class="form">
  <form action="https://formspree.io/paradia@algonquincollege.com" method="POST">
  <input type="hidden" name="_next" value="http://cg.algonquindesign.ca/topics/thanks.html" />
  <input type="hidden" name="_subject" value="Student Feedback" />
    <div class="item">
      <label for="my-semester">I am currently in </label>
      <select id="my-semester" name="my-semester">
        <option>Semester One</option>
        <option>Semester Two</option>
        <option>Semester Three</option>
        <option>Semester Four</option>
        <option>Semester Five</option>
        <option>Semester Six</option>
      </select>
    </div>
    <div class="item">
      <fieldset name="course-rating">
          <legend>How would you rate this course to date?</legend>

          <input type="radio" id="course-rating" name="course-rating" value="Terrible">
          <label for="terrible">Terrible</label>

          <input type="radio" id="course-rating" name="course-rating" value="Poor">
          <label for="poor">Poor</label>

          <input type="radio" id="course-rating" name="course-rating" value="Okay">
          <label for="okay">Okay</label>

          <input type="radio" id="course-rating" name="course-rating" value="Good">
          <label for="good">Good</label>

          <input type="radio" id="course-rating" name="course-rating" value="Very good">
          <label for="very-good">Very good</label>

          <input type="radio" id="course-rating" name="course-rating" value="Fantastic!">
          <label for="fantastic">Fantastic!</label>
      </fieldset>
  </div>
  <div class="item">
    <div>
    <label for="message">What, if anything, could the professor do differently to be of benefit to you going forward in this course?</label>
    </div>
    <textarea id="message" placeholder="Remember, be nice!" cols="60" rows="5" name="Comment"></textarea>
  </div>
    <div class="item">
    <label>
      <input type="submit" value="Submit Form" />
    </label>
    </div>
  </form>
  </div>
---
