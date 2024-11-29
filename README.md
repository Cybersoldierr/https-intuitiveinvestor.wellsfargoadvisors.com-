
<h1>Hack your website Cyber security Intelligence </h1>
<h1>It is a subdomain takeover vulnerability </h1>
    .  ..            .              .                <h1>Impact of Subdomain takeover</h1>
    <h5>It’s very easy to sign up for a new account and claim the subdomain name.

By getting access of a subdomain, an attacker can completely clone of the site, steal valuable credentials like admin accounts (by adding a login form that will redirect the user to a certain page) , steal cookies, or completely destroy the credibility of your company.

It is a covert operation so even the domain owner won’t notice, even your IDS can’t monitor this.

This Vulnerability can lead to other high risk vulnerabilities like Authentication bypass, CORS bypass & many.

</h5>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin Panel</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <!-- Sidebar -->
    <aside class="sidebar">
      <div class="sidebar-header">
        <h2>Admin Panel</h2>
      </div>
      <nav class="sidebar-nav">
        <ul>
          <li><a href="#">Dashboard</a></li>
          <li><a href="#">Users</a></li>
          <li><a href="#">Settings</a></li>
          <li><a href="#">Reports</a></li>
          <li><a href="#">Analytics</a></li>
          <li><a href="#">Logout</a></li>
        </ul>
      </nav>
    </aside>

    <!-- Main Content -->
    <main class="main-content">
      <header class="main-header">
        <h1>Dashboard</h1>
        <div class="user-info">
          <p>Welcome, Admin</p>
          <button class="logout-btn">Logout</button>
        </div>
      </header>

      <section class="dashboard-content">
        <div class="card">
          <h3>Total Users</h3>
          <p>1,234</p>
        </div>
        <div class="card">
          <h3>Revenue</h3>
          <p>$12,345</p>
        </div>
        <div class="card">
          <h3>Reports</h3>
          <p>45</p>
        </div>
        <div class="card">
          <h3>Analytics</h3>
          <p>89%</p>
        </div>
      </section>
    </main>
  </div>
</body>
</html>
