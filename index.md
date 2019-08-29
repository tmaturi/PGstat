<table style="width:100%">
  <tr>
    <th> Surname </th>
    <th> Firstname </th> 
    <th> Nationality</th>
     <th> Remarks  </th>
  </tr>
  {% for student in site.data.phdstudents %}
  <tr>
    <th>{{ student.surname }}</th>
    <th>{{ student.firstname }}</th> 
    <th>{{ student.nationality }}</th>
     <th>{{ student.remarks }} </th>
  </tr>
  {% endfor %}
  </table>
