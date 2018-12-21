
# UrbanCode's Windmill theme for MkDocs
Based on the outstanding mkdocs theme with a focus on navigation and usability, from Grist Labs.

Highlights:
- Convenient navigation for larger documentation projects.
- Retains state of the navigation menu across page transitions.
- Search with term highlighting.
- User may search in a quick dropdown or load results in a full page.
- Default mkdocs theme within pages, including syntax highlighting.
- UrbanCode specific theme changes

## Quick start

1. Clone the directory locally.
2. Add the following snippet to your docs' `mkdocs.yml` file"
```
theme:
    name: null
    custom_dir: {INSTALL_DIR}/mkdocs_windmill
    # Copy settings from mkdocs_theme.yml, which is ignored by custom_dir themes.
    static_templates: [404.html]
    search_index_only: true
    include_search_page: true
```
Full Directions:  [Customization](https://gristlabs.github.io/mkdocs-windmill/#customization/) for extra configuration options that Windmill supports.

3. Model the reset of your `mkdocs.yml` file based on the one in this folder.
4. Run `mkdocs serve` in your mkdocs folder.
