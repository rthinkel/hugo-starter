# Hugo Starter Site

This project is meant to be cloned for future websites. The idea is to have a centralized code-base for the content to sit on top of, with changes and updates being able to be applied to multiple site automatically.

Each subsequent clone is meant to have individual design assets associated with its respective project, while all still relying on a shared set of pre-built assets and references.

Additionally, a shared set of NPM packages will be baked into each project allowing us to create a framework of existing tools. HUGO will manage and build these packages for us.

More documentation to come.

## Installation

This section is still under construction.

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/rthinkel/hugo-starter.git
git submodule add https://github.com/rthinkel/tailwind-starter.git themes/tailwind-starter
```

## Configuration

#### Tailwind Starter Theme

The main framework selected is Tailwind-CSS. The Tailwind-starter theme is loaded as a submodule in the 'themes/' folder, and is merely a way to pipeline the actual Tailwind codebase and additional NPM components into our HUGO site. Additionally, our theme will bundle, minify, fingerprint and compile our sass files automatically using [HUGOs pipeline functionality](https://www.regisphilibert.com/blog/2018/07/hugo-pipes-and-asset-processing-pipeline/).

Each sites design will be handled in its respective root layout folder, rather than the 'Tailwind-starter' theme folder.

#### NPM Packages

* Tailwind CSS
* jQuery
* Algolia Search
* Netlify Identity
* Netlify CMS

#### Netlify Functionality

* Forms & Alerts
* Functions (Algolia, Code Optimization)

## Design & Layouts

Each site will have its own custom layout, as created in the root 'layouts/' folder. I plan on making a base theme that can be forked and then cloned (rather than added as a submodule) to create a few designs to choose from.