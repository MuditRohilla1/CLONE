<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Social Media Web App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1 {
      color: #333;
    }

    h2 {
      color: #555;
    }

    pre {
      background-color: #f0f0f0;
      padding: 10px;
      border-radius: 5px;
      white-space: pre-wrap;
      word-wrap: break-word;
    }

    code {
      background-color: #f9f9f9;
      padding: 2px 4px;
      border-radius: 3px;
      font-family: "Courier New", Courier, monospace;
    }

    ul {
      list-style-type: disc;
      margin-left: 20px;
    }

    .folder-structure {
      white-space: pre-wrap;
      background-color: #f8f8f8;
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    a {
      color: #007bff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>Social Media Web App</h1>
    <p>A full-stack social media web application built using <strong>Mongoose</strong>, <strong>Express</strong>, <strong>React</strong>, <strong>Tailwind CSS</strong>, and <strong>JavaScript</strong>. The app allows users to interact, share posts, and engage with one another on a modern social platform.</p>

    <h2>Features</h2>
    <ul>
      <li><strong>User Authentication</strong>: Secure login and signup functionality with JWT.</li>
      <li><strong>Post Creation & Interaction</strong>: Users can create, like, comment, and delete posts.</li>
      <li><strong>User Profiles</strong>: Customizable user profiles with the ability to add profile pictures and bio.</li>
      <li><strong>Responsive Design</strong>: Optimized for both desktop and mobile using <strong>Tailwind CSS</strong>.</li>
      <li><strong>Real-Time Notifications</strong>: Get notified of new likes, comments, and followers (optional if implemented).</li>
      <li><strong>Follow/Unfollow</strong>: Users can follow or unfollow other users.</li>
      <li><strong>Explore Section</strong>: Discover trending posts and new users.</li>
    </ul>

    <h2>Tech Stack</h2>
    <h3>Frontend:</h3>
    <ul>
      <li><a href="https://reactjs.org/">React</a>: JavaScript library for building user interfaces.</li>
      <li><a href="https://tailwindcss.com/">Tailwind CSS</a>: Utility-first CSS framework.</li>
      <li>Axios: For making HTTP requests to the backend.</li>
    </ul>

    <h3>Backend:</h3>
    <ul>
      <li><a href="https://expressjs.com/">Express</a>: Web framework for Node.js.</li>
      <li><a href="https://mongoosejs.com/">Mongoose</a>: ODM for MongoDB.</li>
      <li>JWT: For user authentication and authorization.</li>
    </ul>

    <h3>Database:</h3>
    <ul>
      <li><a href="https://www.mongodb.com/">MongoDB</a>: NoSQL database for data storage.</li>
    </ul>

    <h2>Installation</h2>
    <ol>
      <li>Clone the repository:</li>
      <pre><code>git clone https://github.com/yourusername/social-media-app.git</code></pre>

      <li>Navigate to the project folder:</li>
      <pre><code>cd social-media-app</code></pre>

      <li>Install dependencies for both frontend and backend:</li>
      <pre><code>npm install
cd client && npm install</code></pre>

      <li>Set up environment variables:
        <ul>
          <li>Create a <code>.env</code> file in the root directory.</li>
          <li>Add the following variables:</li>
        </ul>
        <pre><code>MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret</code></pre>
      </li>

      <li>Run the app:</li>
      <pre><code># Run the backend
npm run server

# Run the frontend
cd client && npm start</code></pre>
    </ol>

    <h2>Folder Structure</h2>
    <div class="folder-structure">
      <pre><code>root/
│
├── client/              # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/              # Express backend
│   ├── models/          # Mongoose schemas
│   ├── routes/          # API routes
│   ├── controllers/     # Controllers for handling logic
│   └── server.js        # Entry point for the backend
│
├── .env                 # Environment variables
├── package.json         # Project dependencies
└── README.md            # Project documentation
      </code></pre>
    </div>

    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
  </div>
</body>

</html>
