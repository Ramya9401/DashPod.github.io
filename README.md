# Employee Details

<h3>Index</h3>
<ol>
<li><a href="#Introduction">Introduction</a></li>
<li><a href="#Flowchart">Flow Chart</a></li>
<li><a href="#algorithm">Algorithms</a>
  <ul>
    <li><a href="#main">Main Program</a></li>
     <li><a href="#create">Create Employee Details</a></li>
     <li><a href="#getpsn">Get Person Details</a></li>
     <li>Get salary details</li>
     <li>validation of name</li>
     <li>validation of date</li>
     <li>Print the employee details</li>
    </ul>
  </li>
    </ol><br>

<h3 id="Introduction">Introduction</h3>
<p>The document briefs you on the program <b>Employee Details</b> using Structures. This program explains the usage of structure within structure and accesing of variables using pointers.</p><br>

<h3 id="Flowchart">Flow Chart</h3>

<br>
<h3 id="algorithm">Algorithms</h3>
<h4 id="main">Main Program</h4>
<ol>
<li>Start the Program.</li>
<li>Create structure for person details as <i>person</i> including firstname,lastname,date-of-birth and assign a variable to structure as <i>psn</i>.</li>
<li>Create structure for salary details as <i>salary</i> including initial salary,increment percentage,current salary,date-of-joining and assign a variable to structure as <i>sal</i>.</li>
<li>Create structure for employee details as <i>employee</i> including pointer variable of type struct person, pointer variable of type struct salary and assign a variable to structure as <i>emp</i>.</li>
<li>Declare variables single pointer "emp1", double pointer "new_emp" of type <i>emp</i> .</li>
<li>Assign address of "emp1" to "new_emp".</li>
<li>Call <i>Create</i> function passing the adress of "new_emp" as argument.</li>
<li>Call <i>Print</i> function passing the adress of "new_emp" as argument.</li>
</ol>

<h4 id="create">Create Employee Details</h4>
<ol>
<li>Allocate the memory of size struct <i>emp</i> to "new_emp".</li>
<li>Allocate the memory of size struct <i>sal</i> to struct sal variable in "new_emp".</li>
<li>Allocate the memory of size struct <i>psn</i> to struct psn variable in "new_emp".</li>
<li>Call <i>get_psn</i> function by passing adress of struct psn variable in "new_emp" to get person details. </li>
  <li>Call <i>get_sal</i> function by passing adress of struct sal variable in "new_emp" to get salary details. </li>
</ol>

<h4 id="getpsn">Get Person Details</h4>
<ol>
  <li>Get firstname from user input into address of struct <i>psn</i> "fname" variable.</li>
  <li>Call <i>checkpsn_name</i> function for validation by passing the "fname" address.</li>
  <li>Get lastname from user input into address of struct <i>psn</i> "lname" variable.</li>
  <li>Call <i>checkpsn_name</i> function for validation by passing "lname" address.</li>
  <li>Get date-of-birth from user input into address of struct <i>psn</i> "dob" variable.</li>
  <li>Call <i>check_dov</i> funciton for validating the date by passing "dob" variable as argument. </li>
</ol>
