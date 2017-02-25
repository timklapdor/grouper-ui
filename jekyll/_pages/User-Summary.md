---

title: User Summary
layout: page
permalink: "/User-Summary"

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
          <div class="col-sm-offset-2 col-sm-10">
            <button type="submit" class="btn btn-default btn-block" name="_action_testOut" value="Generate test output">Generate test output</button>
            <button type="submit" class="btn btn-primary btn-block" name="_action_selectSurvey" value="GO">GO</button>
          </div>
      </div>

</form>
