# Tables
Creating tables:
<img width="707" alt="Screen Shot 2022-10-04 at 12 40 58" src="https://user-images.githubusercontent.com/84048634/193899979-1b3a451f-6921-449b-93b0-ff355299a6c5.png">




Table Rows:
<table>
  <tr>
  </tr>
  <tr>
  </tr>
</table>

Table Data:
   <tr>
      <td> Adam's Greenwork </td>
      <td> 14 </td>
      <td> Package Items </td>
    </tr>
    
Table border using CSS:
table, td {
  border: 1px solid black;
}

Spanning Columns:
Data can span columns using the colspan attribute. The attribute accepts an integer (greater than or equal to 1) to denote the number of columns it spans across.
Eg: <tr>
    <td colspan="2">Out of Town</td>
    <td>Back in Town</td>
  </tr>
  
Spanning Rows:
The rowspan attribute is used for data that spans multiple rows (perhaps an event goes on for multiple hours on a certain day). It accepts an integer (greater than or equal to 1) to denote the number of rows it spans across.
Eg:   <tr> <!-- Row 2 -->
    <th>Morning</th>
    <td rowspan="2">Work</td>
    <td rowspan="3">Relax</td>
  </tr>
  
Table Body:
The <tbody> element should contain all of the table’s data, excluding the table headings.
Eg: <tbody>
    <tr>
      <th></th>
      <th>Saturday</th>
      <th>Sunday</th>
    </tr>
    <tr>
      <th>Morning</th>
      <td rowspan="2">Work</td>
      <td rowspan="3">Relax</td>
    </tr>
  </tbody>
  
Table Head:
The table headings are contained inside of <thead>. Note that the table’s head still requires a row in order to contain the table headings. Additionally, only the column headings go under the <thead> element. We can use the scope attribute on <th> elements to indicate whether a <th> element is being used as a "row" heading or a "col" heading.

Table Footer:
The footer contains the totals of the data in the table. Footers are often used to contain sums, differences, and other data results. Eg:  
<tfoot>
    <tr>
      <th>Total</th>
      <td>$12.5M</td>
    </tr>
 </tfoot>
 
 <img width="706" alt="Screen Shot 2022-10-04 at 13 28 08" src="https://user-images.githubusercontent.com/84048634/193908540-d8fda80e-676c-438d-b565-6be73db4426d.png">


<img width="680" alt="Screen Shot 2022-10-04 at 13 28 37" src="https://user-images.githubusercontent.com/84048634/193908601-1b5d6372-0415-498a-abbe-0497e9bb22e6.png">


