// json2html.js
export default function json2html(data) {
  // Create table header with fixed columns Name, Age, and Gender
  let html = `<table data-user="meghanareddybellamkonda970@gmail.com">
    <thead>
      <tr><th>Name</th><th>Age</th><th>Gender</th></tr>
    </thead>
    <tbody>`;

  // Iterate over data to create table rows
  data.forEach(row => {
    html += `<tr>
      <td>${row.Name || ''}</td>
      <td>${row.Age || ''}</td>
      <td>${row.Gender || ''}</td>
    </tr>`;
  });

  // Close table tags
  html += `</tbody>
  </table>`;

  // Return the generated HTML string
  return html;
}
