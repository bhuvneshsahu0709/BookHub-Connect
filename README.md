<a name="readme-top"></a>

# **BookHub-Connect**
BookHub-Connect provides users with a seamless shopping experience, offering a wide range of books across various genres and categories. Key features include a user-friendly interface, advanced search and filtering options, user reviews and ratings, and personalized book recommendations.

## **Tech Stack** 🛠<a name="tech-stack"></a>

This project was built using a variety of modern technologies and tools:

<details>
  <summary><b>Frontend</b></summary>
  
  - [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
  - [Redux Toolkit](https://redux-toolkit.js.org/) - State management for React applications.
  - [React Router](https://reactrouter.com/) - Routing library for React applications.
  - [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework.
  - [Axios](https://axios-http.com/) - A promise-based HTTP client for making requests to your API.
</details>
<details>
<summary><b>Backend</b></summary>

  - Bookstore API: The custom API created for this project.
    - [API Documentation](https://microverse.notion.site/Bookstore-API-51ea269061f849118c65c0a53e88a739): Documentation for the Bookstore API.
</details>
<details>
<summary><b>Version Control</b></summary>

  - [Git](https://git-scm.com/) - Distributed version control system.
  - [GitHub](https://github.com/) - Web-based platform for version control and collaboration.
</details>
<details>
<summary><b>Other Tools</b></summary>

  - [VS Code](https://code.visualstudio.com/) - A lightweight code editor by Microsoft.
</details>

Our project leverages these technologies to deliver a modern and efficient web application.


## **Table of Contents**

- [Tech Stack 🛠](#tech-stack)
- [Getting Started 💻](#getting-started)
  - [Prerequisites 🧱](#prerequisites)
  - [Installation 🏗️](#installation)
  - [Setting Up Environment Variables ⚙️](#setting-up-environment-variables)
- [Running the Application 📋](#running-the-application)
- [Project Structure 📗](#project-structure)
- [Usage 📂](#usage)
- [Contributing 🤝](#contributing)
- [Acknowledgements 🙏](#acknowledgments)
- [License 📝](#license)
- [Overview 📷](#overview)

## **Getting Started** 💻<a name="getting-started"></a>

### **Prerequisites** 🧱<a name="prerequisites"></a>
Before you begin, ensure you have met the following requirements:

- Node.js: Download and install Node.js from the **[official website](https://nodejs.org/)**.
- npm (Node Package Manager): npm is included with Node.js. Make sure you have npm installed as well.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### **Installation** 🏗️<a name="installation"></a>

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/lily4178993/bookstore-cms.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bookstore-cms
    ```
3. Install the project dependencies:
    ```bash
    npm install
    ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### **Setting Up Environment Variables** ⚙️<a name="setting-up-environment-variables"></a>

The Bookstore CMS uses environment variables to configure certain settings. To set up these variables, follow these steps:

1. Create a **`.env`** file in the project's root directory:
    ```bash
    touch .env
    ```
2. Open the **`.env`** file in a text editor of your choice.

3. Define the following environment variables in the **`.env`** file:
    ```bash
    REACT_APP_URL=your_api_url_here
    REACT_APP_KEY=your_api_key_here
    ```
    Replace **`your_api_url_here`** and **`your_api_key_here`** with the appropriate values for your API setup.

4. Save the **`.env`** file.

Now, the project is configured to use your custom environment variables.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## **Running the Application** 📋<a name="running-the-application"></a>

To run the application locally, use the following command:

**1. Fixing JavaScript/JSX Errors**

To identify and automatically fix JavaScript/JSX errors using ESLint, run the following command:
  ```bash
   npx eslint "**/*.{js,jsx}" --fix
  ```
  ESLint will analyze your code and attempt to fix any issues automatically.

**2. Fixing CSS/SCSS Errors**

To identify and automatically fix CSS/SCSS errors using Stylelint, run the following command:
  ```bash
   npx stylelint "**/*.{css,scss}" --fix
  ```
  Stylelint will analyze your CSS and SCSS files and attempt to fix any issues automatically.
<p align="right">(<a href="#readme-top">back to top</a>)</p>
**3. Run the Development Server**
  ```bash
   npm start
  ```
  This command will start the development server, and the application will be accessible at **`http://localhost:3000`** in your web browser.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## **Project Structure** 📗<a name="project-structure"></a>

The project is organized as follows:

- `src/`: Contains the source code of the application.
  - `components/`: Contains reusable React components.
  - `redux/`: Manages the application state using Redux.
  - `assets/`: Stores static assets like images and icons.
  - `containers/`: Defines the main pages of the application.
- `App.js`: The root component of the application.
- `.env`: Configuration file for environment variables.
- `README.md`: This documentation file.
- `package.json`: Defines project metadata and dependencies.
- `public/`: Contains static files like the HTML template and the project's favicon.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## **Usage** 📂<a name="usage"></a>

- Navigate to the **[Books](http://localhost:3000/)** page to view, add, and edit books.
- Use the **[Categories](http://localhost:3000/categories/All)** page to categorize books by genre.
- Easily manage your book collection using the intuitive user interface.
<p align="right">(<a href="#readme-top">back to top</a>)</p>