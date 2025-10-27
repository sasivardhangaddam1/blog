Starter for the official Gatsby blog theme
Quickly get started using the Gatsby blog theme! This starter creates a new Gatsby site that is preconfigured to work with the official Gatsby blog theme.

🚀 Quick start
Create a Gatsby site.

Use the Gatsby CLI to create a new site, specifying the blog theme starter.

# create a new Gatsby site using the blog theme starter
gatsby new my-themed-blog https://github.com/gatsbyjs/gatsby-starter-blog-theme
Start developing.

Navigate into your new site’s directory and start it up.

cd my-themed-blog/
gatsby develop
Open the code and start customizing!

Your site is now running at http://localhost:8000!

To get started, check out the guide to using the Gatsby blog theme starter, or the longer, more detailed tutorial.

🧐 What's inside?
Here are the top-level files and directories you'll see in a site created using the blog theme starter:

gatsby-starter-blog-theme
├── content
│   ├── assets
│   │   └── avatar.png
│   └── posts
│       ├── hello-world.mdx
│       └── my-second-post.mdx
├── src
│   └── gatsby-theme-blog
│       ├── components
│       │   └── bio-content.js
│       └── gatsby-theme-ui
│           └── colors.js
├── .gitignore
├── .prettierrc
├── gatsby-config.js
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
/content: A content folder holding assets that the theme expects to exist. This will vary from theme to theme -- this starter is set up to get you started with the blog theme, which expects an image asset for your avatar, and blog post content. Replace the avatar image file, delete the demo posts, and add your own!

/src: You will probably want to customize your site to personalize it. The files under /src/gatsby-theme-blog shadow, or override, the files of the same name in the gatsby-theme-blog package. To learn more about this, check out the guide to getting started with using the blog theme starter.

.gitignore: This file tells git which files it should not track / not maintain a version history for.

.prettierrc: This file tells Prettier which configuration it should use to lint files.

gatsby-config.js: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. When using themes, it's where you'll include the theme plugin, and any customization options the theme provides.

LICENSE: Gatsby is licensed under the MIT license.

package-lock.json (See package.json below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. (You won’t change this file directly).

package.json: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

README.md: A text file containing useful reference information about your project.

🎓 Learning Gatsby
Looking for more guidance? Full documentation for Gatsby lives on the website.

Here are some places to start:

Themes
To learn more about Gatsby themes specifically, we recommend checking out the theme docs.
General
For most developers, we recommend starting with our in-depth tutorial for creating a site with Gatsby. It starts with zero assumptions about your level of ability and walks through every step of the process.

To dive straight into code samples, head to our documentation. In particular, check out the Reference Guides and Gatsby API sections in the sidebar.
