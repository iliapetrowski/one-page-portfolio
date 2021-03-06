
## How to Start

With Portfolio Minimal, you get up and running in just a few minutes.

1. **Install the Gatsby CLI.**

   ```
   npm install -g gatsby-cli

   ```

2. **Create a new Gatsby site with the Portfolio Minimal starter.**

   ```
   gatsby new portfolio-minimal https://github.com/konstantinmuenster/gatsby-starter-portfolio-minimal
   ```

3. **Start the site in `develop` mode.**

   ```
   cd portfolio-minimal
   gatsby develop
   ```

4. **Open the source code and start editing!**

---

## Edit Content

After you installed the starter project, you most likely want to add your own content.

### Edit configuration

First, you want to edit the config file which stores the site's configuration (e.g. title, description) and social profiles.

```
|-- src
    |-- config
        |-- index.js
```

Navigate to the `index.js` file in the config folder, edit the configuration, save it, that's it!

### Edit section content

Next, you can edit the content for each section you want to be displayed. By default, all sections are shown. If you want to remove certain sections from the site, check out <a href="#editing-page-structure">this part of the Readme</a>.

```
|-- src
    |-- content
        |-- about
        |-- contact
        |-- hero
        ...
```

You find all content in the content folder (surprisingly). For content integration, the project uses MDX, a Markdown format. If you haven't worked with Markdown or MDX before, check the Markdown syntax in <a href="https://www.gatsbyjs.org/docs/mdx/markdown-syntax/" target="_blank">Gatsby's docs</a>. They also provide <a href="https://www.gatsbyjs.org/docs/mdx/writing-pages/" target="_blank">further information about MDX</a>.

To get up and running, just edit the predefined data fields in each `mdx` file. 

---

## Edit Theme

You find the theme settings in the following file: `src/styles/Theme.js`

There, you can change colors, breakpoints, fonts, and other design-related properties.

---

## Edit Page Structure

To remove or reorder predefined sections, navigate to the `src/pages/index.js` file. This is the home page of your site.

Each section (besides the Articles section) exists of an imported React component and a GraphQL query that is needed for data querying.

**If you want to remove a section**, just delete the imported React component and query.

**If you want to reorder your sections**, just reorder the React components inside the `<Layout />` component.

### Add custom sections

If you want to add your own custom sections, there is a section template you can use. You can find it in the following directory: `src/components/templates`

---

## Feedback

Designing and building a portfolio from scratch can be tough. To inspire you and provide you a foundation to build upon, I've decided to publish [my personal website](https://konstantin.digital) as a Gatsby Starter. This boilerplate project should motivate you to build your own awesome portfolio with Gatsby.

I always appreciate feedback, so share your thoughts and suggestions with me: [mail@konstantin.digital](mailto:mail@konstantin.digital)

If you find any bugs or have feature suggestions, create a new issue or pull request 🙏

Thanks a lot for using this starter! 💪

---

## License

Distributed under the [MIT](http://showalicense.com/?fullname=Konstantin+M%C3%BCnster&year=2019#license-mit) license. 

See ``LICENSE`` for more information.