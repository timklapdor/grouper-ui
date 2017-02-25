---

title: Select Survey
layout: page
permalink: "/Select-Survey"

---

<p>User data will NOT be editable, as this data will come from the LTI link.</p>

<div class="container">
  <form class="form-horizontal" action="http://localhost:8080/GTSurvey/displaySurvey" method="post">
      <div class="form-group">
          <label for="SubjectId" class="col-sm-2 control-label">SubjectId: </label>
            <div class="col-sm-10">
              <input type="text" class="form-control" name="subID" value="ITC182" readonly="readonly" id="subID">
            </div>
      </div>

      <div class="form-group">
          <label for="usrName" class="col-sm-2 control-label">User Name: </label>
            <div class="col-sm-10">
              <input type="text" class="form-control" name="usrName" value="abc123" id="usrName">
            </div>
      </div>

      <div class="form-group">
          <label for="fName" class="col-sm-2 control-label">First name: </label>
            <div class="col-sm-10">
              <input type="text" class="form-control" name="fName" value="Fred" id="fName">
            </div>
      </div>

      <div class="form-group">
          <label for="lName" class="col-sm-2 control-label">Surname: </label>
            <div class="col-sm-10">
              <input type="text" class="form-control" name="lName" value="Nerk" id="lName"><br>
            </div>
      </div>

      <div class="form-group">
        <div class="col-sm-2">
          <p>Select survey from list:</p>
        </div>
        <div class="col-sm-10">
            <select class="form-control" name="id" id="id">
      <option value="4">Has data</option>
      <option value="5">Second survey</option>
      <option value="6">Entered 9 jan</option>
      <option value="7">New 10 Jan </option>
      <option value="8">Read test data</option>
      <option value="9">Testing selone</option>
      <option value="10">New survey name here</option>
      <option value="11">Testing select many</option>
      </select>
      </div>
    </div>

      <div class="form-group">
          <div class="col-sm-offset-2 col-sm-10">
            <button type="submit" class="btn btn-primary btn-block" name="_action_displaySurvey" value="GO">GO</button>
          </div>
      </div>

  </form>
