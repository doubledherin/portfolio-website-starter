<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby Gallery Starter
</h1>

This is a Gatsby implementation of [Start Bootstrap's Creative] (https://startbootstrap.com/previews/creative/) template based on [**John J Kerry's Gatsby starter**](https://johnjkerr.github.io/gatsby-creative).

## ✨ Features

- [React Bootstrap](https://react-bootstrap.github.io)
- [Start Bootstrap Creative](https://startbootstrap.com/previews/creative)
- [GitHub Actions](https://github.com/features/actions)
- [React Scrollspy](https://github.com/makotot/react-scrollspy)

## 🚀 Getting Started

0. **Make sure you have the basics.**

    ***Node.js***
    In order to use this template, you need to have node.js installed. Run `node -v` on the command line, and if a version is displayed, you're good to go. If not, check out Gatsby's instructions on the [**appropriate installation**](https://www.gatsbyjs.org/tutorial/part-zero/#install-nodejs-for-your-appropriate-operating-system) for your machine.

    ***Git***
    If you don't have Git, get it using [**these instructions**](https://www.gatsbyjs.org/tutorial/part-zero/#install-git).

    ***Gatsby CLI***
    You'll need to install this node.js package globally, with `npm install -g gatsby-cli`. Once it's installed, view the available commands by running `gatsby --help`.

1.  **Create a Gatsby site.**
    Use the Gatsby CLI to create a new site, specifying the starter project.
    
    ```sh
    gatsby new <your-project-name> https://github.com/doubledherin/portfolio-website-starter.git
    ```

    This will create a new Gatsby project based on a clone of this repo.

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd <your-project-name>
    gatsby develop
    ```

    You'll see that Git is already initialized in your repo. To push to Github, create a new repository on Github and then add it as the origin remote locally with `git remote add origin <url-of-your-github-repo>`. 

    Make your first commit and push with 
    ```sh
    git add .
    git commit -m "Initial commit"
    git push -f origin master
    ```

    You should only need the `-f` (force push) tag the first push.

3.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is GraphiQL, a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `<your-project-name>` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

    Hot reloading is hot hot hot.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## 💫 Deployment

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/JohnJKerr/gatsby-creative)

### GitHub Actions x GitHub Pages

This project also contains an example of [GitHub Actions](https://github.com/features/actions) deployment to [GitHub Pages](https://pages.github.com). View the [`deploy.yml`](https://github.com/JohnJKerr/gatsby-creative/blob/master/.github/workflows/deploy.yml) for the build definition.

The build process deploys to a folder rather than the root, and therefore uses the `--pages-prefix` flag in the build step and `pathPrefix: '/gatsby-creative'` in [`gatsby-config.js`](https://github.com/JohnJKerr/gatsby-creative/blob/master/gatsby-config.js).

#### Access Token

If you wish to use the GitHub Actions workflow to deploy to GitHub Pages you will need to add an `ACCESS_TOKEN` secret to your repository

Go to https://github.com/settings/tokens to generate a Personal Access Token and add it to your account. The token will need the following permissions:

- repo
- read:packages
- write:packages

Make a copy of your token as you will not be able to access it again.

Return to your repository, go to settings and add a secret with the name `ACCESS_TOKEN`.

The Action will then deploy your site to `{your-github-pages-url}/{your-repository}`.
 
#### Not Using GitHub Pages?

If you do not wish to use GitHub Pages, simply remove the `/.github/workflows/deploy.yml` file.

<!-- AUTO-GENERATED-CONTENT:END -->
