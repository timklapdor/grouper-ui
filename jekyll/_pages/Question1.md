---

title: Question 1
layout: page
permalink: "/Question1"

---

<p>Question text can appear in this area</p>

<div class="container">
  <form class="form-horizontal" action="http://localhost:8080/GTSurvey/displaySurvey" method="post">

      <div class="form-group">
      <div class="radio">
          <label>
            <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1">
            Option One</label>
          </div>
      <div class="radio">
          <label>
            <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
            Option Two</label>
          </div>
      <div class="radio">
          <label>
            <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3">
            Option Three</label>
          </div>
      <div class="radio">
            <label>
              <input type="radio" name="optionsRadios" id="optionsRadios4" value="option4">
              Option Four</label>
            </div>
      </div>


      <div class="form-group extra-padding">
            <div class="btn-group btn-group-justified" role="group" aria-label="...">
                <div class="btn-group" role="group">
                <button type="button" class="btn">Previous</button>
                </div>
                <div class="btn-group" role="group">
                <button type="button" class="btn btn-default" disabled="disabled">...</button>
                </div>
                <div class="btn-group" role="group">
                <button type="button" class="btn btn-primary">Next</button>
                </div>
                </div>
      </div>
  </form>
