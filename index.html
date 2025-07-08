<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <title>User Info</title>
</head>
<body>
  <form id="form">
    <input type="text" id="name" placeholder="Name" required><br>
    <input type="email" id="email" placeholder="Email" required><br>
    <input type="text" id="username" placeholder="Username" required><br>
    <button type="submit">Submit</button>
  </form>
  <button onclick="viewData()">🔍 View Data</button>

  <pre id="output"></pre>

  <script>
    const API_URL = 'https://your-replit-app.replit.app'; // Replace with your Replit backend URL

    document.getElementById('form').addEventListener('submit', async (e) => {
      e.preventDefault();
      const data = {
        name: document.getElementById('name').value,
        email: document.getElementById('email').value,
        username: document.getElementById('username').value,
      };

      const res = await fetch(API_URL + '/submit', {
        method: 'POST',
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify(data)
      });

      alert(await res.text());
      e.target.reset();
    });

    async function viewData() {
      const res = await fetch(API_URL + '/data');
      const json = await res.json();
      document.getElementById('output').innerText = JSON.stringify(json, null, 2);
    }
  </script>
</body>
</html>
