# awashedupnerd.in

[![A washedup nerd is released under the MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/TeamYayin/awashedupnerd/blob/master/LICENSE)
![Twitter Follow](https://img.shields.io/twitter/follow/anindianjourney?label=Yayin%20AI&style=)

![Publish to Github Pages](https://github.com/TeamYayin/awashedupnerd/workflows/Gatsby%20Publish%20GH-Pages/badge.svg)

Landing Page for the blogs, it features Parallax effects and animations. Made with Gatsby using the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

## ✨ Features

- Theme UI-based theming
- react-spring parallax effect
- CSS Animations on Shapes

## 🚀 Getting Started

[![Fork A Washedup Nerd into CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/TeamYayin/awashedupnerd/tree/master/)

![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

### Push changes using CodeSandbox

After opening the above CodeSandbox link on the new browser window fork it to your Github profile and make the necessary changes and commit. Then make a pull request by comparing only the `master` branch and your repository. For now, [@Prajwal](https://github.com/py563) will handle all PRs.

### Local Developement

> Development tools used were `VSCode`, `WSL`, or `WSL2-Alpine` on `Windows10`. A detailed wiki for tool structure for all blogs would be [here](https://github.com/TeamYayin/awashedupnerd/wiki).

**Requires `Node.js` before proceeding any further install it.**

- Install Gatsby-CLI globally with node package manager `npm install -g gatsby-cli` and to learn more about Gatsby skip to [learning section below](#-learning-gatsby).

- Clone this repository using SSH or HTTPS
  `sh git clone git@github.com:TeamYayin/awashedupnerd.git`  
  `sh git clone https://github.com/TeamYayin/awashedupnerd.git`.

- Navigate into your new site's directory `cd awashedupnerd`.

- Install dependencies `npm install`.

- Start developing, run the project using `gatsby develop`.

### Open the code and start customizing

Your site is now running at `http://localhost:8000`!

If you want to learn more about how you can use a Gatsby starter that is configured with a Gatsby theme, you can check out this [shorter](https://www.gatsbyjs.org/docs/themes/using-a-gatsby-theme/) or [longer](https://www.gatsbyjs.org/tutorial/using-a-theme/) tutorial.

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx` in the `src/@lekoarts/gatsby-theme-cara/sections/` folder.

To add a new project or blog use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### What goes into the `static` folder

The `static` folder contains the icons, social media images, any custom js or CSS files (for better-caching use CDN or npm package for public files) and robots.txt.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation of Gatsby lives [on Gatsby's website](https://www.gatsbyjs.org/).

### Themes

- To learn more about Gatsby's themes specifically, we recommend checking out the [theme docs](https://www.gatsbyjs.org/docs/themes/).

### General

- **For most developers, I recommend starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to Gatsby's documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Reference Guides_ and _Gatsby API_ sections in the sidebar.

### Starters

This project uses starter `gatsby-starter-portfolio-cara`, that creates a new Gatsby site that installs and configures the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

### 🌟 Supporting the author behind this great theme

Please do reach Leko Arts on [Twitter](https://twitter.com/lekoarts_de) and star his [gatsby-themes](https://github.com/LekoArts/gatsby-themes) project, share it on Social Media or consider supporting him on [Patreon](https://www.patreon.com/lekoarts) !

🤔 Questions or problems? with the theme, please open up an issue on the main repository: [LekoArts/gatsby-themes](https://github.com/LekoArts/gatsby-themes) and also do contribute.

Thanks!
