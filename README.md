Download Link: https://assignmentchef.com/product/solved-itse2321-program-12-inheritance
<br>
<strong> </strong>The owners of the Annan Supermarket would like to have a program that computes the monthly gross pay of their non-exempt hourly employees. The user will enter an employee’s first name, last name, the hourly rate of pay, and the number of hours worked for the month, by the week. Assume there are 4 week in a month.  In addition, Annan Supermarkets would like the program to compute the employee’s net pay and overtime pay. <strong>Overtime hours, any hours over</strong> <strong>40, are paid at 1.5 the regular hourly rate.</strong>  Net pay is gross pay minus taxes (Refer to the tax table on the second page). Use Class Scanner to input the user’s data.




Define a class called <strong>HourlyEmployee </strong>that extends the <strong>Employee</strong> Class provided. The class must have <strong>private attributes</strong> regular (≤ 40) and overtime hours worked.  The class must also have member functions to perform the following tasks:




<ul>

 <li>A constructor to initialize the first name, last name, pay rate, and hours worked (See the Employee Class for more details).</li>

</ul>




<ul>

 <li>A setter method to set

  <ul>

   <li>the hours work for the month (<strong>by the week – assume 4 weeks in a month</strong>)</li>

  </ul></li>

</ul>




<ul>

 <li>A getter method to return

  <ul>

   <li>the total regular hours work for the month</li>

   <li>the total overtime hours for the month</li>

  </ul></li>

</ul>




<ul>

 <li>A getter method to return

  <ul>

   <li>the monthly regular pay</li>

  </ul></li>

</ul>




<ul>

 <li>A getter method to return

  <ul>

   <li>the monthly overtime pay</li>

  </ul></li>

</ul>




<ul>

 <li>A method that uses the super class’ toString method to display the output which must include the following information: ⬧ Employee’s first and last name

  <ul>

   <li>Pay rate</li>

   <li>Total hours worked</li>

   <li>Total regular hours worked</li>

   <li>Total overtime hours worked</li>

   <li>Monthly Regular Pay</li>

   <li>Monthly overtime pay</li>

   <li>Monthly gross pay</li>

   <li>Monthly taxes</li>

   <li>Monthly net pay</li>

  </ul></li>

</ul>




Write a test Class named <strong>HourlyEmployeeTest</strong> to test the methods in the <strong>Employee </strong>and <strong>HourlyEmployee</strong> Class.  Allow the user to run the program as many times as possible.

<strong>No input, processing, or output should happen in the main method</strong>.  <strong>All work in the test class should be delegated to other non-static methods in the class</strong>. Include the recommended minimum documentation for each method.  See the program one template for more details.




<strong>Study the Employee Class and understand it before starting the program. </strong>




<strong><u>Tax Table</u></strong>

<strong>                 If the gross  </strong>

<strong>Bracket          pay is over          But not over          Tax </strong>




<ul>

 <li>$0.00 $2,000.00             10%</li>

 <li>$2,000.00 $3,500.00             15%</li>

 <li>$3,500.00 $6,000.00             28%</li>

 <li>$6,000.00 $10,000.00             31%</li>

 <li>$10,000.00 N/A                36%</li>

</ul>

<strong>Test your program with the following data: </strong>

<h1>Run 1                                                                           Run 2</h1>




Name:               John Doe                                           Name:               Jane Doe

Hourly rate:       $35.10                                               Hourly rate:       $37.20

Hours worked:   40, 30, 40, 35                                   Hours worked:  40, 40, 40, 40

<h1>Run 3</h1>




Name:                &lt;Your Name (First Last) &gt;

Hourly rate:        $65.50

Hours worked:   50, 35, 40, 55

Run your program and copy and paste the output to a file.  Create a folder named, <strong>fullname_program12</strong>.  Copy your source code and the output file to the folder.  Zip the folder and upload it to Blackboard.


