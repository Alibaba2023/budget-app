<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [YouPayment App ](#youpayment-app-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
    - [Live demo ](#live-de-)
  - [🔭 Walk through video ](#-walk-through-video-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
    - [Run linters](#run-linters)
    - [Run tests](#run-tests)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

---

<!-- PROJECT DESCRIPTION -->

# YouPayment App <a name="about-project"></a>

**"YouPayment App"** YouPayment is a mobile budget app built with Rails 7 and PostgreSQL. It allows the user to record all their expense transactions and classify them by categories.
---

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://guides.rubyonrails.org/">Ruby on Rails (v7.0.8)</a></li>
    <li><a href="https://www.postgresql.org/docs/">PostgreSQL</a></li>
  </ul>
</details>

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://www.w3schools.com/html/">HTML5</a></li>
    <li><a href="https://www.w3schools.com/css/">CSS</a></li>
    <li><a href="https://www.rubyguides.com/2018/11/ruby-erb-haml-slim/">ERB template</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

<ul>
  <li>Ruby on Rails framework</li>
  <li>
    Use Linters to check code quality
    <ul>
      <li>Rubocop</li>
      <li>Stylelint</li>
    </ul>
  </li>
  <li>MVC architectural/design pattern</li>
  <li>Data persistent in PostgreSQL</li>
  <li>Test the application with rspec and capybara gems</li>
  <li>Authentication system build with devise gem</li>
  <li>Follow Microverse's list of best practices</li>
</ul>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🚀 Live Demo <a name="live-demo"></a>

link to your deployed project.

- [Live Demo Link](https://budget-app-z2pa.onrender.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Walk through video <a name="walk-through-video"></a>

<a href="https://drive.google.com/file/d/11W_0J-RmDL3RqkRky3wwz2DTmvTF-YCQ/view?usp=sharing">Video presentation of the Project</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

<ul>
    <li><p>**A code editor** like Visual Studio Code (Recommended) or any other of your preference. Opening the project and adding or modifying the source code is necessary. [You can Download Visual Studio Code here](https://code.visualstudio.com/)</p></li>
</ul>

<ul>
    <li><p>**Git:** to manage the project versions of source code. [You can Download Git here](https://git-scm.com/)</p></li>
</ul>

<ul>
    <li><p>**Nodejs and NPM:** to install and manage the node packages. [Nodejs and NPM installation guide](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
</p></li>
</ul>

### Setup

Clone this repository to your desired folder by using this 👇️ command :

```
git clone https://github.com/Alibaba2023/budget-app.git
```

### Install

Go to the project directory:

```
 cd budget-app
```

Before running the program, verify that you have Ruby on Rails installed on your OS by running the following command:

```
 rails --version
```

It should show you the version of ruby on rails ​​installed. If this does not happen and only an error message is displayed, you should verify your installation or install Ruby on Rails from scratch.

[Download and Install Ruby on Rails](https://guides.rubyonrails.org/getting_started.html)

Once you have verified that you have Ruby on Rails installed, run the following command to install the necessary gems:

```
 bundle install
```

Then run the following command to install the necessary Node packages:
```
 npm install
```

After installing the gems and packages, run the following command to create the database:

```
 rails db:create
```

Then run the following command to migrate the database:

```
 rails db:migrate
```

### Usage

Run the following command inside the project folder to start the application:

```
 rails s
```

This will start the application on your local server. You can now open your browser and go to http://localhost:3000/ to see the application running.

### Run linters

To verify that the ruby and CSS code is written without errors and meets good practice standards, run the following command inside the project folder:

- **ruby linter:**
```
 rubocop
```

- **CSS linter:**
```
 stylelint "**/*.{css,scss}"
```

### Run tests

To execute the tests, run the following command inside the project folder:

```
  bundle exec rspec
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Ali Baba Hussaini**

- GitHub: [@Alibaba2023](https://github.com/Alibaba2023/)
- LinkedIn [Alibaba Hussaini](https://www.linkedin.com/in/ali-baba-hussaini-630607267/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

Upcoming improvements:

- [x] Add Forms to create a new category and payment
- [x] Add the functionality to list categories and payments
- [x] Add the integration tests using capybara gem
- [x] Create the CSS styles for the app
- [x] Deploy the application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Alibaba2023/budget-app/issues).

To do Contributions, please fork this repository, create a new branch and then create a Pull Request from your branch. You can find detailed description of this process in: [A Step by Step Guide to Making Your First GitHub Contribution by Brandon Morelli](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project and know someone who might find it helpful, please share it.
Or give it a **star** ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

The UI design of this web app is not mine. This design was created and belongs to Gregoire Vella. (Here)[https://www.behance.net/gallery/19759151/Snapscan-iOs-design-and-branding?tracking_source=] You can find more information about the original design of this mobile app and you can also see Gregoire Vella's profile (here)[https://www.behance.net/gregoirevella] to know more details about his wonderful work.

I would also like to thank my Microverse teammates for their support. They have supported me a lot in carrying out this project, giving me suggestions, and good advice and solving my code doubts.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

The UI design of the webpage is not mine. It is under (Creative Commons License)[https://creativecommons.org/licenses/by-nc/4.0/] licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
