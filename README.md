---
permalink: /
eleventyNavigation: { key: Home, order: 1 }
---

<h1><sup style class="faded">Build Awesome</sup> <em>C</em>ontent-First</h1>

![](https://img.shields.io/github/v/release/anyblades/subtle?label=&color=darkslategray&style=for-the-badge)
[![](https://img.shields.io/badge/Demo-blue?logo=netlify&logoColor=white&style=for-the-badge)](https://subtle.blades.ninja/)
[![](https://img.shields.io/badge/Code-gainsboro?logo=github&logoColor=black&style=for-the-badge)](https://github.com/anyblades/subtle)
[![](https://img.shields.io/github/stars/anyblades/subtle?label=Star&labelColor=gainsboro&color=silver&style=for-the-badge)](https://github.com/anyblades/subtle)

<big>Best content-first micro-starter powered by [Build&nbsp;Awesome&nbsp;Kit](//build.blades.ninja/) and [Blades&nbsp;CSS](//blades.ninja/) —
perfect for blogs, docs, landing pages, or anything content-driven.</big>

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
