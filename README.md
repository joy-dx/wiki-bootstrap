# Wiki Starter

A skeleton for the static site generator to build a tech docs wiki system

## Usage

The wiki will automatically bake some useful content relating to environments and roles but, it is very likely you will want to customize the home page and maybe add some custom pages.

The technical wiki will consume directories and markdown pages in the following manner.

* `wiki/_index.md` is the site home page
* `wiki/about.md` (for example) will make a page available at `site_url/about`
* `wiki/test/first.md` (for example) will make a page available at `site_url/test/first`
* For displaying custom pages within the top navigation, include the following frontmatter `menus: main`
* Putting environment and role specifications within the respective paths will automatically create content pages and menu entries