# Portfolio Website Workshop

Welcome to the Portfolio Website Workshop! In this workshop, you will create and deploy your own portfolio website using GitHub, GitHub Codespaces, and Vercel. Follow the steps below to get started.

## Introduction

In this workshop, you will learn how to:
1. Create a GitHub account.
2. Fork a starter portfolio repository.
3. Customize your portfolio using GitHub Codespaces.
4. Deploy your portfolio on Vercel.

By the end of this workshop, you will have a live portfolio website that you can share with friends, family, and potential employers.

## Step-by-Step Instructions

### Step 1: Setting Up

#### Create a GitHub Account
1. Visit [GitHub](https://github.com).
2. Click on "Sign up" in the top right corner.
3. Follow the instructions to create a new account.

#### Sign in to GitHub
1. Once your account is created, sign in to GitHub.

### Step 2: Forking the Starter Project

#### Search for the Portfolio Repository
1. In the GitHub search bar, type the name of the starter portfolio repository (provided by the instructor).
2. Click on the repository name in the search results to open it.

#### Fork the Repository
1. Click on the "Fork" button in the top right corner of the repository page.
2. This will create a copy of the repository under your own GitHub account.

### Step 3: Opening the Repository in Codespaces

#### Open GitHub Codespaces
1. In your forked repository, click on the "Code" button.
2. Select "Open with Codespaces" and then "Create new Codespace on main."

#### Working in Codespaces
1. Wait for Codespaces to set up your environment (this may take a few minutes).
2. Once ready, you will see an online code editor where you can edit the project files.

### Step 4: Customizing the Portfolio

#### Editing the HTML and CSS
1. In Codespaces, open the `index.html` file.
2. Make changes to personalize the content, such as updating your name, adding your bio, and listing your projects.
3. Open the `styles.css` file and customize the styles as desired.

#### Saving Your Changes
1. Once you have made your changes, save the files.
2. GitHub Codespaces automatically saves changes, but make sure you commit your changes.

#### Committing Your Changes
1. In the terminal (or source control tab), add your changes with the following commands:
    ```sh
    git add .
    git commit -m "Customized portfolio content"
    git push
    ```

### Step 5: Deploying to Vercel

#### Sign Up for Vercel
1. Visit [Vercel](https://vercel.com).
2. Click on "Sign Up" and create an account using your GitHub account for easy integration.

#### Import Project from GitHub
1. Once logged in to Vercel, click on "New Project."
2. Select "Import Git Repository" and authorize Vercel to access your GitHub repositories.
3. Select your forked portfolio repository and click "Import."

#### Deploy the Project
1. Vercel will automatically detect the project settings.
2. Click "Deploy" to start the deployment process.

#### View Your Live Site
1. After the deployment is complete, Vercel will provide a URL for your live site.
2. Visit the URL to see your portfolio website live.

### Additional Tips

- **Enhancements:** Add more sections, such as skills, hobbies, and a blog.
- **Media:** Add images and links to your projects or social media profiles.
- **Responsive Design:** Ensure the site looks good on mobile devices by learning basic responsive design principles.

---

## Example Portfolio Repository

You can create a starter portfolio repository with the following structure:

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>
    <section>
        <h2>About Me</h2>
        <p>Hello! I am a high school student learning web development.</p>
    </section>
    <section>
        <h2>Projects</h2>
        <ul>
            <li>Project 1</li>
            <li>Project 2</li>
        </ul>
    </section>
    <footer>
        <p>Contact: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
    </footer>
</body>
</html>
```

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}
header {
    background-color: #4CAF50;
    color: white;
    padding: 1em 0;
}
section {
    margin: 20px;
}
footer {
    background-color: #f1f1f1;
    padding: 1em 0;
}
```
