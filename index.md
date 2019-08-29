<table style="width:100%">
  {% for student in site.data.phdstudents %}
  <tr>
    <th>{{ student.surname }}</th>
    <th>{{ student.firstname }}</th> 
    <th>{{ student.nationality }}</th>
     <th>{{ student.remarks }} </th>
  </tr>
  {% endfor %}
  </table>
