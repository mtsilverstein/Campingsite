<html>
<h1 id="title">Camping Survey</h1>
<p1 id="Description">Enter your infomation and choose camping prefrences below </p1>

<br><br>

<form id="survey-form" onsubmit="scamAlert()">

    <script>
        function scamAlert(){
            alert("Congrats you've been scammed!");
}
    </script>
  <label id="labelName">Name:</label>
  <br>
  <input type="Name" placeholder="Enter your Name">
 
         
  <br><br>
  <label id="ssnumb"> Social Security # (secured)</label>
    <br>
    <input type="ssnumb" placeholder="Enter your SS #">
   
  <br><br>
  <label id="momsmaiden"> Mothers Maiden Name</label>  
  <br>
  <input type="momsmaiden" placeholder="Enter mothers maden name">

    <br><br>
    
  <label id="email">Email:</label>
 <br>
  <input type="email" placeholder="Enter your email">

 <br><br>
  
  <label id="number">Age(optional):</label>
  
  <br>
  
<input type="number" name="age" id="numberz" min="10" max="99" class="form-control" placeholder="Age">
  
  <br><br>
  
  <p2>Where would you like to go camping most?</p2>
 <select id="locations" name="locations">
  <option value="sand-dunes">Sand Dunes</option>
  <option value="black-canyon">Black Canyon</option>
  <option value="buena-vista">Buena Vista</option>
  <option value="idaho-springs">Idaho Springs</option>
   </select>
  <br><br>
  
  <p3> What time would you be ready to leave</p3>
  <br>
<input type="radio" id="time1" name="time" value="before-noon">
<label for="before-noon">Before Noon</label>
  
  <input type="radio" id="time2" name="time" value="before3">
<label for="before3">Before 3 p.m</label>  
  <input type="radio" id="time3" name="time" value="before5">
<label for="before5">Before 5 p.m</label> 
  <br>  
  
  <div class="form-group">
<button type="submit" id="submit" class="submit-button">
Submit
</button>
</div>
  </form>
  </html>
