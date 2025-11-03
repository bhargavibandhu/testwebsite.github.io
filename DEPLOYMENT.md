# How to Deploy Your Website

Here are instructions on how to deploy your website and make it live. We'll cover two popular and easy-to-use services: Netlify and GitHub Pages.

## Option 1: Deploying with Netlify

Netlify is a great option for deploying static websites. They offer a generous free tier.

1.  **Sign up for Netlify:** Go to [netlify.com](https://www.netlify.com/) and sign up for a free account. You can sign up with your GitHub, GitLab, or Bitbucket account.

2.  **Drag and Drop Deployment:**
    *   Once you're logged in, you'll be taken to your dashboard.
    *   Simply drag the folder containing your `index.html`, `style.css`, and `images` directory from your computer and drop it onto the Netlify dashboard.
    *   Netlify will automatically deploy your site and give you a unique URL (e.g., `random-name-12345.netlify.app`).

3.  **Deploying from a Git Repository (Recommended):**
    *   If your code is in a Git repository (like GitHub), you can connect it to Netlify for continuous deployment.
    *   From your Netlify dashboard, click "New site from Git".
    *   Choose your Git provider (GitHub, GitLab, Bitbucket) and authorize Netlify to access your repositories.
    *   Select the repository containing your website.
    *   Netlify will automatically detect the build settings. For a simple HTML/CSS/JS site, you can leave the build command and publish directory fields blank.
    *   Click "Deploy site". Netlify will build and deploy your site. Now, every time you push changes to your repository, Netlify will automatically redeploy your site.

4.  **Custom Domain:**
    *   You can change the random site name to something more memorable in the site settings.
    *   You can also add a custom domain that you own. Follow the instructions in the Netlify documentation to set up your custom domain.

## Option 2: Deploying with GitHub Pages

If your code is already on GitHub, GitHub Pages is a very convenient way to host your site for free.

1.  **Create a GitHub Repository:**
    *   If you haven't already, create a new repository on GitHub and push your website files (`index.html`, `style.css`, `images/`) to it.

2.  **Enable GitHub Pages:**
    *   Go to your repository on GitHub.
    *   Click on the "Settings" tab.
    *   In the left sidebar, click on "Pages".
    *   Under "Source", select the branch you want to deploy from (usually `main` or `master`).
    *   Leave the folder as `/ (root)`.
    *   Click "Save".

3.  **Access Your Site:**
    *   After a few minutes, your site will be deployed.
    *   You'll see a green bar with the URL of your live site at the top of the "Pages" settings. The URL will be in the format `https://<your-username>.github.io/<your-repository-name>/`.

---

That's it! Your website is now live. If you make any changes to your files, you'll need to re-upload them to Netlify (if using drag and drop) or push the changes to your Git repository (if connected to Netlify or using GitHub Pages).
