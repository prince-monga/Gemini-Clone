<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Gemini Clone Project 🌐</h1>
    <p>Welcome to the Gemini Clone Project! This is a React JS application that replicates the features and functionality of the Gemini platform, with components built from scratch and API integration to fetch real-time data.</p>
  </header>

  <nav>
    <ul>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#problem-statement">Problem Statement</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#technologies-used">Technologies Used</a></li>
      <li><a href="#deployment">Deployment</a></li>
      <li><a href="#how-to-clone-and-run-locally">How to Clone and Run Locally</a></li>
      <li><a href="#api-integration">API Integration</a></li>
      <li><a href="#contact-information">Contact Information</a></li>
    </ul>
  </nav>

  <section id="introduction">
    <h2>🔰 Introduction</h2>
    <p>Hello! I’m <strong>Prince Monga</strong>, a passionate <strong>Frontend Developer</strong> and the <strong>co-founder of VidiPixels</strong>, a platform for digital excellence. This project, <strong>Gemini Clone</strong>, is my first attempt at building a React JS application with API integration. The goal is to replicate the key features of the Gemini platform while showcasing my skills in creating dynamic, data-driven React applications.</p>
    <ul>
      <li>Built using <strong>ReactJS</strong> for frontend development.</li>
      <li>API integration to fetch real-time data and display it dynamically.</li>
      <li>Component-based architecture for maintainable and reusable code.</li>
    </ul>
  </section>

  <section id="problem-statement">
    <h2>🚩 Problem Statement</h2>
    <p>The Gemini platform provides a dynamic user interface that requires an interactive frontend to display data and provide real-time updates. The traditional approach to building such a platform lacks the ability to interact with data efficiently. This project addresses the need to:</p>
    <ul>
      <li>Fetch real-time data using an API for dynamic updates.</li>
      <li>Enhance <strong>user engagement</strong> through a seamless and responsive frontend.</li>
      <li>Improve <strong>code reusability</strong> with React components.</li>
      <li>Optimize <strong>development speed</strong> with hooks and other modern React features.</li>
    </ul>
  </section>

  <section id="features">
    <h2>🚀 Features</h2>
    <ul>
      <li><strong>Real-time Data Fetching</strong>: Integration with an API to get live data and display it.</li>
      <li><strong>Responsive Design</strong>: Ensures a smooth experience on all devices, from mobile to desktop.</li>
      <li><strong>Dynamic Components</strong>: Built using React components that fetch and display data based on user interaction.</li>
      <li><strong>State Management</strong>: Handled efficiently with React hooks, including useState and useEffect.</li>
    </ul>
  </section>

  <section id="technologies-used">
    <h2>💻 Technologies Used</h2>
    <table>
      <tr>
        <th>Technology</th>
        <th>Purpose</th>
      </tr>
      <tr>
        <td><strong>ReactJS</strong></td>
        <td>Frontend library for building dynamic user interfaces.</td>
      </tr>
      <tr>
        <td><strong>React Router</strong></td>
        <td>For navigating between different views within the app.</td>
      </tr>
      <tr>
        <td><strong>Axios</strong></td>
        <td>To handle API requests and fetch data asynchronously.</td>
      </tr>
      <tr>
        <td><strong>CSS Modules</strong></td>
        <td>Scoped styling for individual components to avoid conflicts.</td>
      </tr>
      <tr>
        <td><strong>Netlify</strong></td>
        <td>Deployment platform for hosting the live application.</td>
      </tr>
    </table>
  </section>

  <section id="deployment">
    <h2>🌍 Deployment</h2>
    <p>The project is deployed on <strong>Netlify</strong>.</p>
    <p>👉 <a href="https://gemini-clone.netlify.app" target="_blank">Live Demo</a></p>
  </section>

  <section id="how-to-clone-and-run-locally">
    <h2>📂 How to Clone and Run Locally</h2>
    <h3>Prerequisites</h3>
    <ul>
      <li>Node.js installed on your system.</li>
      <li>Basic knowledge of React and NPM/Yarn.</li>
    </ul>
    <h3>Steps to Clone:</h3>
    <pre>
      git clone https://github.com/prince-monga/gemini-clone.git
      cd gemini-clone
      npm install
      npm start
    </pre>
    <p>Open <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> in your browser to view the app.</p>
  </section>

  <section id="api-integration">
    <h2>🔗 API Integration</h2>
    <p>For this project, I have integrated the <strong>Gemini API</strong> (or another relevant API) to fetch real-time data and display it dynamically within the application. Key features include:</p>
    <ul>
      <li><strong>Data Fetching</strong>: Axios is used to make GET requests to the API.</li>
      <li><strong>State Management</strong>: Data is stored and managed in React state using <strong>useState</strong>.</li>
      <li><strong>Side Effects</strong>: API calls are handled inside <strong>useEffect</strong> to manage lifecycle events and ensure data is fetched when the component mounts.</li>
    </ul>
  </section>

  <section id="contact-information">
    <h2>📞 Contact Information</h2>
    <ul>
      <li>📧 Email: <a href="mailto:princearora1309@gmail.com"><i class="fas fa-envelope"></i> princearora1309@gmail.com</a></li>
      <li>💼 LinkedIn: <a href="https://www.linkedin.com/in/prince-monga-/"><i class="fab fa-linkedin"></i> LinkedIn Profile</a></li>
      <li>🖥️ GitHub: <a href="https://github.com/prince-monga"><i class="fab fa-github"></i> GitHub Profile</a></li>
    </ul>
  </section>

  <footer>
    <p>👋 About Me</p>
    <p>I’m Prince Monga, a passionate Frontend Developer and the co-founder of VidiPixels. This project showcases my ability to integrate APIs with React and create modern, responsive web applications. Feel free to explore and contribute to the project!</p>
    <p>🌟 If you like this project, please give it a star! 🌟</p>
  </footer>
</body>
</html>
