## Welcome to My GitHub Repository!

### About README Files

Hey there! If you stumbled upon this README file, you're in the right place! README files are like the welcoming doormats of GitHub repositories. They provide helpful information about what you'll find inside and how to navigate through it.

### What's This?

Welcome! This repository, named `calebrlx.github.io`, is your gateway to the online world. With GitHub Pages, you can host your very own website for free, right here on GitHub. Simply create an account, name your repository `yourusername.github.io`, and voila! Your website will be accessible at `yourusername.github.io`. It's that easy!


---

### Let's Build Your First Website!

#### Method 1: GitHub Web Interface

1. **Create Your Repository:**
   - Go to your GitHub homepage and click on the "New" button to create a new repository.
   - Name it `[your username].github.io`.
   - Click "Create repository".

2. **Add HTML File:**
   - Click on the "Add file" dropdown and select "Create new file".
   - Name the file `index.html`.
   - Copy the HTML code provided in the tutorial and paste it into the file.

3. **Commit Your Changes:**
   - Scroll down to the commit section.
   - Write a brief message describing your changes (e.g., "Added index.html").
   - Click "Commit changes".

4. **View Your Website:**
   - Wait for a minute or so for GitHub to process your changes.
   - Open a new tab in your browser and go to `https://[your username].github.io`.
   - You should see the text you added in the HTML file displayed on the page.

5. **Customize Your Website:**
   - Explore GitHub to find other GitHub Pages repositories [here](https://github.com/topics/githubio).
   - Find a repository with a website design you like.
   - Copy the HTML, CSS, and other necessary files into your repository to customize your website.


---

#### Method 2: GitHub.dev (GitHub's Online IDE)

1. **Access GitHub.dev:**
   - Press "." while in your repository to open GitHub.dev, GitHub's online IDE.
   - On the left sidebar, click on the gear icon at the bottom, then select "Themes" and choose a dark theme.

2. **Create HTML File:**
   - Click on the "Files" tab.
   - Hover over the repository name and select the "+" icon to create a new file named `index.html`.
   - Paste the HTML code provided in the tutorial into the file.

3. **Commit Your Changes:**
   - Click on the "Source Control" icon (three dots connected in a branch pattern).
   - You'll see your changes listed under "Changes".
   - Enter a brief commit message describing your changes.
   - Click "Commit".

4. **View Your Website:**
   - Wait for a minute or so for GitHub to process your changes.
   - Open a new tab in your browser and go to `https://[your username].github.io`.
   - Your website should now display the text you added in the HTML file.


---

<details open>
<summary>Basic code</summary>

```
<!DOCTYPE html>
<html>
    <head>
        <!-- This is a comment and won't effect the code -->
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!-- Basic Meta Tags -->
        <title>Website</title> <!-- This will change the text on the page tab -->
        <link rel="icon" href="/img.png" type="image/png" sizes="32x32" /> <!-- This controls the favicon, the little image you see on google next to websites and on the left of the title -->
        <meta name="description" content="Some cool site I found."> <!-- Not that important, mostly for seo related stuff -->
        <style>
            /* Basic styling for the webpage */
            body {
                font-family: Arial, sans-serif; /* Set font family */
                margin: 0; /* Remove default margin */
                padding: 0; /* Remove default padding */
                text-align: center; /* Center-align text */
                background-color: #f8f8f8; /* Set background color */
                color: #333; /* Set text color */
                line-height: 1.6; /* Set line height for better readability */
            }

            /* Styling for main content area */
            main {
                padding: 20px; /* Add padding */
            }

            /* Styling for headings */
            h1, h2, h3 {
                color: #007bff; /* Set heading color */
            }

            /* Styling for paragraphs */
            p {
                margin-bottom: 20px; /* Add bottom margin for spacing */
            }
        </style> <!-- Styling con be put in here using css -->
    </head>
    <body>
        <main> <!-- Basic divider, usefull for more complex layouts and styling -->
            <h1>Hey!</h1> <!-- Basic header text, equal to # in markdown -->
            <h3>Sub-hey</h3> <!-- Basic header text, equal to ### in markdown -->
            <p>something something</p> <!-- Basic paragraph text -->
        </main>
    <body>
</html>
```
</details>


---

### Other Useful Tips and Tricks

<details closed>
<summary>Explore Further</summary>

#### Public Folder Access

Did you know that anything you place in the `public` folder of your GitHub Pages repository becomes accessible through your website's URL? For instance, if you upload an image named `img.png` into the `public` folder (`public/img.png`), you can access it on your website at `yoursite.com/img.png`. This feature comes in handy when you want to include images, downloadable files, or other resources on your website.

#### Routing Basics

Understanding routing is key to organizing your website's content. Each HTML file you create in your repository represents a path on your website. The `index.html` file serves as the homepage (`yoursite.com`). For example, if you create a file named `about.html` and publish your site, you can access it at `yoursite.com/about`. This allows you to structure your website with different pages and sections for easy navigation.

#### Licensing Your Code

Before you dive too deep into coding, it's essential to understand licenses, especially if you're using open-source software or sharing your own projects. Common licenses like MIT and Apache offer permissions and limitations for using and modifying code. For instance, the MIT license generally allows for free use, modification, and redistribution of code with limited liability. Make sure to review the specific terms of each license to understand your rights and responsibilities.

#### Embrace Frameworks

Frameworks can be your best friend when it comes to building and maintaining larger websites. While they may add some complexity, they streamline the development process and help you create robust, scalable web applications. Consider exploring popular frameworks like Bootstrap, React, or Vue.js to see how they simplify web development tasks and enhance user experience. You can learn a lot by studying the source code of open-source projects built with these frameworks.

#### Resources for Further Learning

- **GitHub Pages Documentation**: Dive deeper into GitHub Pages functionality and features by exploring the [official documentation](https://docs.github.com/en/pages).
- **HTML and CSS Tutorials**: Brush up on your HTML and CSS skills with online tutorials and resources such as [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) and [W3Schools](https://www.w3schools.com).
- **Understanding Licenses**: Learn more about software licenses and their implications through resources like [Choose a License](https://choosealicense.com/) and [Open Source Initiative](https://opensource.org/).
- **Exploring Frameworks**: Explore different web development frameworks by checking out their official documentation, tutorials, and GitHub repositories. Experiment with building small projects to get hands-on experience.

#### Try Vercel for Hosting

Looking for more control and flexibility over your website hosting? Consider using [Vercel](https://vercel.com), a platform that offers a generous free tier and supports a wide range of open-source projects. With Vercel, you can sign up using your GitHub account and easily deploy repositories straight from their platform. The best part? Anytime you commit changes to your GitHub repository, Vercel automatically redeploys your website, keeping it up to date without any manual intervention. You'll receive a URL (e.g., `yourproject.vercel.app`) where you can view your live webpage. And if you want to share your website with others, you can use a link shortener like [v.gd](https://v.gd) to create a more user-friendly URL.

#### Understanding Git and GitHub

While GitHub offers a plethora of features tailored for professionals, it's essential to understand the basics of Git, the version control software that powers it. At its core, "committing" in Git is akin to saving your work with extra features. It allows you to track changes to your codebase over time, making it invaluable for managing larger projects with multiple collaborators. While Git may seem intimidating at first, it's widely used and relatively easy to learn with practice.

#### Getting Started with Git

If you're new to Git, fear not! It's pre-installed on most computers, and you can start using it right away. Here's how:
- **Mac**: Open Terminal (you can find it by pressing Space + Command and typing "Terminal") and start typing Git commands.
- **Windows**: Consider installing a Unix-like environment such as Git Bash or Windows Subsystem for Linux (WSL) for a smoother Git experience. (The gist of this was "windows is trash" but the ai made it more "friendly", if your using windows, look up how to use it. I dont use windows.)
- **Linux**: If you're using Linux, you're likely already familiar with the command line interface and can start using Git right away.

#### Cloning Repositories

Want to download a GitHub repository to your local machine? It's as easy as running a single command! Here's how:
1. Copy the URL of the GitHub repository you want to clone. Make sure it's in the format `https://github.com/[username]/[reponame]` (without `.dev` or anything after the repository name).
2. Open your terminal and navigate to the directory where you want to clone the repository.
3. Run the command `git clone [githuburl]`, replacing `[githuburl]` with the URL you copied.
4. Voila! Git will clone the repository to your local machine, allowing you to explore and modify the code as needed.

Remember, if your repository is set to private visibility, you may need to authenticate with your GitHub credentials to clone it successfully.

#### Resources for Further Learning

- **Vercel Documentation**: Explore Vercel's features and functionalities by diving into their [official documentation](https://vercel.com/docs).
- **Git Handbook**: Get acquainted with Git's basic concepts and commands through resources like the [Git Handbook](https://guides.github.com/introduction/git-handbook/).
- **GitHub Learning Lab**: Take interactive courses on Git and GitHub offered by GitHub's [Learning Lab](https://lab.github.com/).
- **Git Cheat Sheet**: Keep a handy [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) nearby for quick reference while learning Git commands.

With these additional insights and resources, you're well-equipped to navigate the world of Git, GitHub, and web hosting platforms like Vercel. Happy coding!
</details>


---

### Additional Resources

<details closed>
<summary>Explore Further</summary>

#### Favorite Open Source Projects

Here are some of my personal favorite open-source projects that you might find interesting:
- **[Next.js](https://nextjs.org)**: A powerful framework for building React applications with server-side rendering and other advanced features.
- **[Chadnext](https://github.com/../chadnext)**: A basic Software as a Service (SaaS) application built using Next.js, showcasing its capabilities in real-world projects.

#### Amazing Websites and Platforms

Discover some amazing websites and platforms that offer valuable resources for developers and enthusiasts alike:
- **[Hugging Face Chat](https://huggingface.co/chat)**: Explore the latest AI models for free and without an account. Try out various AI capabilities and applications.
- **[Hugging Face](https://huggingface.co)**: An incredible platform with access to source code for AI models and other resources, fostering collaboration and innovation in the AI community.
- **[Vercel](https://vercel.com)**: A hosting platform for webpages that offers a generous free tier and seamless deployment of projects from GitHub.
- **[Railway](https://railway.app)**: Another hosting platform, focused on providing resources like APIs and databases. More technical, but offers powerful capabilities.
- **[AWS](https://aws.amazon.com)**: A comprehensive hosting platform with a wide range of services. While more complex, it's widely used at enterprise scales and powers a significant portion of the internet.

#### Essential Tools and Platforms

Explore some essential tools and platforms that can enhance your development experience:
- **[ChatGPT](https://chat.openai.com)**: Access the free 3.5 model for generating text and engaging in conversations. Consider upgrading to the Plus version for even more capabilities.
- **[OpenAI API](https://platform.openai.com)**: Dive into the technical aspects of AI development with OpenAI's API. Check out the documentation for detailed information on integrating AI into your applications.
- **[Visual Studio Code](https://code.visualstudio.com)**: A lightweight, feature-rich code editor that's perfect for local development. Completely free and open-source, with a vibrant ecosystem of extensions.
- **[Docker](https://docker.com)**: Learn about containerization and defining how applications run. Docker simplifies deployment and ensures consistency across different environments.
- **[SoloLearn](https://www.sololearn.com)**: An excellent platform for learning the basics of various programming languages. Available as an app, it offers interactive lessons and challenges.
- **Pythonista**: An iOS app that provides a convenient environment for writing and running Python scripts on your iPhone or iPad. Ideal for quick prototyping and experimentation.

#### Additional Learning Resources

- **[Next.js Documentation](https://nextjs.org/docs)**: Dive into the official documentation to master the Next.js framework and its advanced features.
- **[GitHub Learning Lab](https://lab.github.com/)**: Explore interactive courses on Git, GitHub, and other development topics offered by GitHub's Learning Lab.
- **[FreeCodeCamp](https://www.freecodecamp.org/)**: Access free coding tutorials and projects to build your skills and enhance your portfolio.
- **[Codecademy](https://www.codecademy.com/)**: Learn to code interactively with step-by-step tutorials covering various programming languages and technologies.

With these resources at your disposal, you're well on your way to becoming a proficient developer and exploring exciting projects in the world of open source and beyond!
</details>


---

### Essential Terms Explained

<details closed>
<summary>Learn More</summary>

#### Git
- **Git**: A distributed version control system used for tracking changes in code files. It allows multiple developers to collaborate on a project simultaneously.

- **Pull**: The action of fetching changes from a remote repository and integrating them into the local repository.

- **Merge**: Combining changes from different branches or histories into a single branch.

- **Main**: The default branch in a Git repository, often used as the primary development branch.

- **Version Control**: The management of changes to documents, computer programs, large web sites, and other collections of information.

- **Commit**: A snapshot of changes made to a repository at a specific point in time.

- **Repository (Repo)**: A storage location where software packages, libraries, and other data are stored and managed.

- **Source Code**: The human-readable version of a computer program before it's been compiled or translated into binary code.

- **Fork**: A copy of a repository that allows you to freely experiment with changes without affecting the original project.

- **Issues**: Problems, suggestions, or questions related to a project that are tracked on platforms like GitHub for discussion and resolution.

- **Contribute**: To actively participate in the development or improvement of a project, typically by submitting code changes, bug fixes, or enhancements.

- **Push**: The action of sending changes from a local repository to a remote repository.

#### Networking
- **HTTP (Hypertext Transfer Protocol)**: A protocol used for transmitting data over the internet.

- **HTTPS (Hypertext Transfer Protocol Secure)**: A secure version of HTTP that encrypts data during transmission.

- **TLD (Top-Level Domain)**: The last part of a domain name, such as ".com" or ".org".

- **Subdomain**: A domain that is part of a larger domain, appearing before the main domain name.

- **Port**: A numerical identifier used to specify a particular process or application running on a computer in a network.

- **Proxy**: An intermediary server that forwards requests from clients to other servers.

- **IP (Internet Protocol)**: A unique numerical address assigned to each device connected to a computer network.

- **DNS (Domain Name System)**: A hierarchical decentralized naming system for computers, services, or other resources connected to the internet.

- **Records**: Data entries in a DNS zone file that map domain names to corresponding IP addresses.

- **Domain**: A unique name that identifies one or more IP addresses.

- **URL (Uniform Resource Locator)**: A web address that specifies the location of a resource on the internet.

- **URI (Uniform Resource Identifier)**: A string of characters used to identify a resource, either by location, name, or both.

- **Cookies**: Small pieces of data stored on a user's device by websites to remember user preferences, login credentials, and other information.

- **Inspect**: To examine or analyze the code, structure, or behavior of a website or application.

- **Web Console**: A tool in web browsers that allows developers to interact with a web page using JavaScript commands.

#### CLI (Command-Line Interface)
- **CLI**: A text-based interface used to interact with a computer program or operating system.

- **Navigation**: Basic commands for navigating the file system, such as listing files (`ls`), changing directories (`cd`), creating directories (`mkdir`), and editing files (`vim`).

- **npm (Node Package Manager)**: A package manager for JavaScript and Node.js projects, used for installing and managing dependencies.

- **pnpm**: Another package manager for JavaScript projects, designed to be faster and more efficient than npm.

- **yarn**: A third package manager for JavaScript projects, developed by Facebook and optimized for performance and reliability.

- **pip**: The package installer for Python, used for installing and managing Python packages.

#### Languages
- **Shell (.sh)**: A scripting language used for automating tasks in Unix-based systems.

- **TypeScript (.ts, .tsx)**: A superset of JavaScript that adds static typing and other features for building large-scale applications.

- **JavaScript (.js, .jsx)**: A versatile programming language used for creating dynamic, interactive websites and web applications.

- **JSON (.json)**: A lightweight data interchange format used for storing and exchanging data between a server and a web application.

- **Python (.py)**: A high-level programming language known for its simplicity and readability, widely used for web development, data analysis, and artificial intelligence.

- **Swift (.swift)**: A programming language developed by Apple for building iOS, macOS, watchOS, and tvOS applications.

#### Files
- **README.md**: A file containing information about a project, typically written in Markdown format for easy readability on platforms like GitHub.

- **index.html**: The main HTML file of a website, serving as the entry point for visitors.

- **package.json**: A metadata file used in Node.js projects to define project details and dependencies.

- **yarn.lock**: A file generated by the Yarn package manager that locks dependency versions to ensure consistent installations across different environments.

- **.git**: The hidden directory that contains all the version control information for a Git repository.

- **docker-compose.yml**: A configuration file used by Docker Compose to define services, networks, and volumes for a multi-container Docker application.

- **Dockerfile**: A text file containing instructions for building a Docker image, which can be used to create containers for running applications.

#### Other
- **Syntax**: The rules and structure governing the combination of symbols and words in a programming language or markup language.

- **Bug**: An error or flaw in a computer program that produces unexpected results or behavior.

With these terms explained, you'll have a better understanding of the fundamental concepts and tools used in programming and web development.
</details>



<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>This or That</title>
<style>
    .content {
        display: none;
    }

    .active {
        display: block;
    }
</style>
</head>
<body>
<button onclick="showThis()">This</button>
<button onclick="showThat()">That</button>

<div id="thisContent" class="content active">
    <h2>This Content</h2>
    <p>This is the content for the "This" option.</p>
</div>

<div id="thatContent" class="content">
    <h2>That Content</h2>
    <p>This is the content for the "That" option.</p>
</div>

<script>
    function showThis() {
        document.getElementById("thisContent").classList.add("active");
        document.getElementById("thatContent").classList.remove("active");
    }

    function showThat() {
        document.getElementById("thatContent").classList.add("active");
        document.getElementById("thisContent").classList.remove("active");
    }
</script>
</body>
</html>
