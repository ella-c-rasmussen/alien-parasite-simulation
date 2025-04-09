# simulation-template

This is a *bare-minimum* template to create a simulation site.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

After completing the creation of your new site on GitHub, update it as needed:

## Replace the content of the template pages

Update the following files to your own content:

- `index.md` (your new home page)
- `README.md` (information for those who access your site repo on GitHub)

You may update or delete other `.md` files as needed.

## Publishing your site on GitHub Pages

1.  If your created site is `YOUR-USERNAME/YOUR-SITE-NAME`, update `_config.yml` to:

    ```yaml
    title: YOUR TITLE
    description: YOUR DESCRIPTION
    footer_content: 'YOUR FOOTNOTE.'
    ```

2.  Push your updated `_config.yml` to your site on GitHub.

3.  In your newly created repo on GitHub:
    - 
    - if there were any failed Actions, go to the `Actions` tab and click on `Re-run jobs`.

## Supporting discussions

[giscus](https://giscus.app/) is a comment system powered by GitHub Discussions. You could use this feature for
facilitating communication among players, submitting reports, and/or collecting feedback. To enable it,
config your giscus app, add the JavaScript code to `_includes/head_custom.html`, and create a `.giscus` container
where you like to insert the comment box:

```html
<div id="giscus"></div>
```
