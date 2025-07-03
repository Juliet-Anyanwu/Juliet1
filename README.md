<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Salesforce Admin Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f9fafb;
    }
    .project-card:hover {
      transform: translateY(-4px);
      transition: all 0.3s ease-in-out;
    }
  </style>
</head>
<body class="text-gray-800">

  <!-- Header -->
  <header class="bg-white shadow p-6 text-center">
    <img src="https://i.imgur.com/gICI6nr.jpeg" alt="Juliet Anyanwu Profile Photo" class="mx-auto mb-4 w-32 h-32 rounded-full border-4 border-blue-200 object-cover shadow-md">
    <h1 class="text-4xl font-bold mb-2">Juliet Anyanwu</h1>
    <p class="text-lg">Certified Salesforce Administrator | CRM Analytics | Automation | Data Optimization</p>
  </header>

  <!-- About Section -->
  <section class="p-10">
    <h2 class="text-2xl font-bold mb-4">About Me</h2>
    <p class="text-gray-700 max-w-4xl mx-auto">
      I'm a Salesforce Administrator passionate about delivering efficient, scalable CRM solutions. WIth over five years of experience, my focus areas include automations, data management, integrations, and adoption strategies — all designed to increase operational efficiency and user satisfaction.
    </p>
  </section>

  <!-- Projects Section -->
  <section class="p-10 bg-gray-100">
    <h2 class="text-2xl font-bold mb-6">Portfolio Projects</h2>

    <div class="grid md:grid-cols-2 gap-8">
      <!-- Project Card Example -->
      <div class="bg-white rounded-2xl shadow-lg p-6 project-card">
        <h3 class="text-xl font-semibold mb-2">1. Lead Assignment Automation</h3>
        <p class="text-sm text-gray-600 mb-2"><strong>Pain Point:</strong> Sales reps were manually assigning leads, causing delays and inconsistencies.</p>
        <p class="text-sm text-gray-600 mb-2"><strong>Actions Taken:</strong> Designed a Flow using Salesforce’s Flow Builder to auto-assign leads based on region and product interest.</p>
        <p class="text-sm text-gray-600 mb-2"><strong>Outcome:</strong> Reduced lead assignment time by 90%, increasing sales rep responsiveness and conversion rate.</p>
        <div class="mt-4">
          <img src="images/lead_flow_example.png" alt="Lead Flow Screenshot" class="rounded-lg border">
        </div>
      </div>

      <!-- Another Project -->
      <div class="bg-white rounded-2xl shadow-lg p-6 project-card">
        <h3 class="text-xl font-semibold mb-2">2. Data Quality Dashboard</h3>
        <p class="text-sm text-gray-600 mb-2"><strong>Pain Point:</strong> Leadership lacked visibility into duplicate and incomplete data.</p>
        <p class="text-sm text-gray-600 mb-2"><strong>Actions Taken:</strong> Built CRM Analytics dashboards to flag data anomalies, duplicates, and missing fields.</p>
        <p class="text-sm text-gray-600 mb-2"><strong>Outcome:</strong> Enabled weekly data scrubs, improved reporting accuracy, and enhanced strategic decisions.</p>
        <div class="mt-4">
          <img src="images/data_dashboard.png" alt="Data Dashboard" class="rounded-lg border">
        </div>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section class="p-10">
    <h2 class="text-2xl font-bold mb-4">Skills & Tools</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-sm text-gray-700">
      <span class="bg-white p-2 rounded shadow">Salesforce Flows</span>
      <span class="bg-white p-2 rounded shadow">CRM Analytics</span>
      <span class="bg-white p-2 rounded shadow">Change Management</span>
      <span class="bg-white p-2 rounded shadow">Data Loader</span>
      <span class="bg-white p-2 rounded shadow">Validation Rules</span>
      <span class="bg-white p-2 rounded shadow">Reports & Dashboards</span>
      <span class="bg-white p-2 rounded shadow">Field-Level Security</span>
      <span class="bg-white p-2 rounded shadow">Change Sets</span>
    </div>
  </section>

  <!-- Contact -->
  <footer class="bg-white p-6 text-center">
    <p>📧 onyijuliet5435@gmail.com | 🌍 Vancouver, BC | 🔗 <a href="https://www.linkedin.com/in/juliet-anyanwu-sfadminexpert" class="text-blue-500">LinkedIn</a></p>
  </footer>

</body>
</html>
