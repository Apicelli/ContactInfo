<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      padding: 20px;
    }

    .contact-container {
      max-width: 500px;
      background: #fff;
      padding: 30px;
      margin: 0 auto;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      margin-top: 10px;
    }

    input, textarea {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button {
      margin-top: 20px;
      padding: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0056b3;
    }

    .email-note {
      text-align: center;
      margin-top: 15px;
      font-size: 0.9em;
      color: #555;
    }
  </style>
</head>
<body>

  <div class="contact-container">
    <h2>Contact Us</h2>
    <form action="mailto:dev@jameschasesoftware.com" method="POST" enctype="text/plain">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="6" required></textarea>

      <button type="submit">Send Message</button>
    </form>
    <div class="email-note">
      Or email us directly at <strong>dev@jameschasesoftware.com</strong>
    </div>
  </div>

</body>
</html>
