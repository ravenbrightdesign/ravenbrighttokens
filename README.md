<div align="center">

# IMPORTANT NOTICE: This project is no longer being maintained.

Thank you for your interest in this project.

As of December 11th, 2023, this project is no longer being maintained or updated. The repository will still be available and can be forked, but no further updates or issue responses will be made.

This project is licensed under the terms of the Apache License 2.0. You are free to fork and use this project according to the terms of that license.

Thank you for your understanding and support!

<div align="center">

# Ravenbright Design Tokens

</div>

<div align="center">

[![Known Vulnerabilities](https://snyk.io/test/github/ravenbrightdesign/ravenbrighttokens/badge.svg)](https://snyk.io/test/github/ravenbrightdesign/ravenbrighttokens)
![GitHub last commit](https://img.shields.io/github/last-commit/ravenbrightdesign/ravenbrighttokens)
[![GitHub license](https://badgen.net/github/license/ravenbrightdesign/ravenbrighttokens)](https://github.com/ravenbrightdesign/ravenbrighttokens/blob/main/LICENSE.md)
[![Ravenbrightcss.com](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](http://ravenbrightcss.com)

</div>

---

This repo is a group of design tokens in accordance with [Ravenbright CSS](https://ravenbrightcss.com) to help you enable seamless handoff experience & build intuitive website faster. Ravenbright Design currently offers 4 different design token formats such as JSON, CSS variables, Figma Tokens, & Tailwind CSS config.

<div align="center">

## Download Ravenbright Design Tokens 👇

</div>

<div align="center">

<a href="https://github.com/ravenbrightdesign/ravenbrighttokens">
<img src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white">
</a>
</div>

## Why Ravenbright Design Tokens?

- 🎨 Apply your own custom brand in minutes

- 🤝 Faster & seamless handoff experience between the teams

- ✅ Connected with Ravenbright CSS & its UI collections that available in Next.js, Astro, Gatsby, & HTML5.

- 📉 Reduce duplicate styles in CSS

- 🌐 Platform agnostic. It provides flexible design tokens that works regardless of specific tech platforms.

- 👌 Build intuitive & consistent website faster

- 🚀 Achieve high-performance site with optimized CSS

- 🌙 Support light & dark mode theme

## How to get started?

### Manual download

- Download the source code from [GitHub Releases](https://github.com)

### Use it via CDN

```bash
<link rel="stylesheet" href="https://unpkg.com/ravenbrighttokens/ravenbright-vars.min.css">
```

```bash
<link rel="stylesheet" href="https://unpkg.com/ravenbrighttokens/ravenbright-json.json">
```

```bash
<link rel="stylesheet" href="https://unpkg.com/ravenbrighttokens/ravenbright-figma-tokens.json">
```

### Install via npm

```bash
# initialize project
npm init

# download & install Ravenbright Design Tokens locally
npm install ravenbrighttokens

# change directory
cd node_modules/ravenbrighttokens
```

---

<div align="center">

Still have doubt? Don't be, explore & play around with Ravenbright Design Tokens live demo on Codepen.

## View demo 👇

<a href="https://codepen.io/ariqnarasaputra/pen/QWxmVqq">
<img src="https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white" alt="View demo on Codepen">
</a>
<a href="https://ravenbrightcss.com/uicollections">
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="Explore UI collections">
</a>

</div>

---

## Customization & build process

### JSON

Some of Ravenbright design tokens including colors & typography are initially created from [Figma Tokens plugin](https://figmatokens.com) & then manually edited to enhance & arrange the structure. The plugin helps us making the design works well together with the development process.

After that, you can use [Style Dictionary](https://style-dictionary.io) to generate the tokens into different formats such as CSS variables, SASS variables, Android XML, iOS swift, etc.

### Figma Tokens

Read the tutorial here 👉 [Ravenbright CSS official docs](https://ravenbrightcss.com/docs/integrations/figma).

Currently in Ravenbright Figma Tokens v1.0.0, there exists some **limitations**:

- Colors are the only styles that work out of the box when imported into Figma built-in styles
- CSS box shadow values in JSON are not working when applied to Figma objects or components
- Letter-spacing & line-height values must use a 'px' unit because Figma still doesn't support 'rem' unit. Check [this post on Figma forum](https://forum.figma.com/t/rem-and-font-size-for-inspect/1161/32) for more details.

### CSS variables

Learn more about customizing & building the CSS variables in 👉 [Ravenbright CSS official docs](https://ravenbrightcss.com/docs/usage/cssvariables).

### Tailwind CSS config

At the moment, Tailwind CSS config is manually edited & created from [Figma Tailwind CSS plugin](https://www.figma.com/community/plugin/785619431629077634).
Check the config here 👉 [Ravenbright CSS official docs](https://ravenbrightcss.com/docs/integrations/tailwindcss).

---

## License

Ravenbright Design Tokens are released under [Apache License 2.0](https://github.com/ravenbrightdesign/ravenbrighttokens/blob/main/LICENSE.md).
