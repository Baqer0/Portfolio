<h1>Data Visualisation Projects</h1>
<p>Explore the data visualization projects I have developed:</p>

<table>
  <tr>
    <td align="center" onclick="showProject('youtubersAnalysis')">
      <img src="../asset/Youtubers_analysis.png" width="150" height="150" alt="Youtubers Analysis"/><br/>
      <b>Youtubers Analysis</b>
    </td>
    <td align="center" onclick="showProject('diabetesDashboard')">
      <img src="../asset/Diabetes_Analysis.png" width="150" height="150" alt="Diabetes Health Dashboard"/><br/>
      <b>Diabetes Health Dashboard</b>
    </td>
    <td align="center" onclick="showProject('eCommerceAnalysis')">
      <img src="../asset/E_Commerce_Analysis.png" width="150" height="150" alt="E-Commerce Analysis"/><br/>
      <b>E-Commerce Analysis</b>
    </td>
  </tr>
</table>

<!-- Container for displaying project content -->
<div id="project-details" class="project-details">
  <h2>Click on a project to see details here</h2>
</div>

<!-- JavaScript for dynamic content -->
<script>
function showProject(projectId) {
  let content = '';

  switch (projectId) {
    case 'youtubersAnalysis':
      content = `
        <h2>Youtubers Analysis</h2>
        <p>This project involves analyzing data on YouTubers' engagement, content types, and growth metrics. It provides insights into what makes a channel successful.</p>
        <p>Technologies used: Python, Pandas, Matplotlib, Seaborn.</p>
      `;
      break;
    case 'diabetesDashboard':
      content = `
        <h2>Diabetes Health Dashboard</h2>
        <p>An interactive dashboard designed to monitor and visualize key health metrics related to diabetes management.</p>
        <p>Technologies used: Tableau, data wrangling with Python.</p>
      `;
      break;
    case 'eCommerceAnalysis':
      content = `
        <h2>E-Commerce Analysis</h2>
        <p>Detailed analysis of e-commerce data to uncover trends, customer behaviors, and performance metrics.</p>
        <p>Technologies used: Python, SQL, data visualization libraries.</p>
      `;
      break;
    default:
      content = `<h2>Click on a project to see details here</h2>`;
  }

  document.getElementById('project-details').innerHTML = content;
}
</script>
