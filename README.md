
# codewile
Codewile is the frontend generated for codewile.com. This is decoupled frontend where the data is provided using GraphQL from a django application (tier.codewile.com)

## Setting up local development environement

1. If you do not have node installed please go ahead and install node in your local development machine
2. Install gatsby-cli `npm install -g gatsby-cli`
3. You may initialise a new gatsby project or bootstrap any gatsby starter pack like `gatsby new folder https://github.com/gatsbyjs/gatsby-starter-hello-world`
4. If you have already cloned your empty git repository move the folders and files from the `folder` to your root working folder to which you cloned your repository

## Netlify setups
1. Login to netlify
2. Click on create new site then Connect to Git provider and Pick a repository 
3. Then you will be able to deploy the site
4. After this you will be able to setups your domain
5. for a domain that you already own please do the following
Point www CNAME record to upbeat-cori-328647.netlify.app
Log in to the account you have with your DNS provider, and add a CNAME record for www pointing to upbeat-cori-328647.netlify.app.

www CNAME upbeat-cori-328647.netlify.app.
Point A record to 75.2.60.5
Create an A record for codewile.com pointing to our load balancer’s IP address 75.2.60.5.

codewile.com A 75.2.60.5


Set up Netlify DNS for your domain

Update your domain’s name servers
Last step! Log in to your domain provider and change your name servers to the following:

dns1.p02.nsone.net
dns2.p02.nsone.net
dns3.p02.nsone.net
dns4.p02.nsone.net


## What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

3.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

4.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

5.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.com/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

6.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.com/docs/gatsby-config/) for more detail).

7.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.com/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

8.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.com/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

9.  **`LICENSE`**: This Gatsby starter is licensed under the 0BSD license. This means that you can see this file as a placeholder and replace it with your own license.

10. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

