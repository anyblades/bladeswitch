---
permalink: /
eleventyNavigation: { key: Home, order: 1 }
content_for_header: <meta property="og:image" content="https://build.blades.ninja/og/content-first.png">
---

<h1>
  <sup style class="faded">Build Awesome<br></sup><!-- <br> for GitHub only -->
  <em>C</em>ontent-First
</h1>

<p>
  <img src="https://img.shields.io/github/v/release/anyblades/buildawesome-content-first?label=&color=darkslategray&style=for-the-badge">
  <a href="https://content.build.blades.ninja/"><img src="https://img.shields.io/badge/Demo_➜-blue?style=for-the-badge" hidden></a><!-- GitHub only -->
  <object data="https://img.shields.io/github/stars/anyblades/buildawesome-content-first?label=GitHub&labelColor=silver&color=gainsboro&style=for-the-badge"></object><!-- won't render on GitHub -->
</p>

<big>Best content-first micro-starter powered by [Build&nbsp;Awesome&nbsp;Kit](//build.blades.ninja/) and [Blades&nbsp;CSS](//blades.ninja/)
—&nbsp;perfect for blogs, docs, landing&nbsp;pages, or&nbsp;anything content-driven.</big>

---

## Feel the difference

By [literally] hiding inside `.build` subfolder, it declutters the project root for your content:

<table class="borderless">
<tr><th>

[buildawesome-content-first](https://github.com/anyblades/buildawesome-content-first)
</th><th>vs.</th><th>

[eleventy-base-blog](https://github.com/11ty/eleventy-base-blog)
</th></tr>
<tr><td><!-- $ tree -L 1 -a -F --dirsfirst -I '.git' --noreport | pbcopy -->

```treeview
├── .build/
├── blog/
├── media/
├── LICENSE.md
├── README.md
└── netlify.toml
```

</td><td></td><td>

```treeview
├── .github/
├── _config/
├── _data/
├── _includes/
├── content/
├── css/
├── public/
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .nojekyll
├── .nvmrc
├── LICENSE
├── README.md
├── eleventy.config.js
├── netlify.toml
├── package-lock.json
├── package.json
└── vercel.json
```

</td></tr></table>
<style>
  .borderless {
    th { padding-bottom: 0 }
    pre { padding: 0; margin: 0 }
  }
</style>

---

## Local development

As simple as:

```sh
cd .build/
npm install    # dependencies
npm start      # development
npm run stage  # serve production version locally
               # ready to deploy! 🚀
```

---

## <sup style>Featured by</sup>

- https://www.11ty.dev/docs/starter/
- https://sveltiacms.app/en/docs/frameworks/eleventy
- https://build.blades.ninja/starters/
- https://11tybundle.dev/starters/
- [awesome-buildawesome](https://github.com/anyblades/awesome-buildawesome)

<!--{.columns}-->
