# David's Personal Resume

This repository is my personal resume created by [JSON Resume](https://jsonresume.org/getting-started/). If you have any suggestions or questions about this blog, feel free to contact me.

* Please visit https://yungshenglu.github.io/resume/ to view the site.

---
## Commands

### Installation

1. Install the [JSON Resume](https://jsonresume.org/getting-started/)
    ```bash
    $ npm install -g resume-cli
    ```
2. Install the theme named [Kendall](http://themes.jsonresume.org/theme/kendall) of the resume
    ```bash
    $ npm install -g jsonresume-theme-kendall
    ```

### Generation

* Export the resume to HTML file with Kendall's theme
    ```bash
    $ resume export --theme kendall index.html
      running validation tests on resume.json ...

    Checking NPM for latest version...
      ✓ Passed all validation tests.
    To publish your resume at https://jsonresume.org type the command resume publish
    Your resume-cli software is up-to-date.

    Done! Find your new .html resume at:
      <PATH_OF_REPO>/index.html
    ```

---
## SEO and Personal Icon

* Add SEO into `index.html`
    ```html
    <!-- SEO -->
    <meta charset="utf-8">
    <meta http-equiv="content-type" content="text/html">
    <meta name="author" content="Yung-Sheng Lu">
    <meta name="copyright" content="Yung-Sheng Lu">
    <meta name="google-site-verification" content="jBJeYf8DAaX6r5eAWLS4_Q5jiRIBS1phgG-C06lSEcA" />
    <meta name="keywords" content="David Lu,davidlu,yungshenglu">
    ```
* Add personal icon into `index.html`
    ```html
    <!-- Icons -->
    <link rel="shortcut icon" href="./public/favicon.ico" type="image/x-icon">
    <link rel="icon" href="./public/favicon.ico" type="image/x-icon">
    ```

---
## Author

* [David Lu](https://github.com/yungshenglu)

---
## License

[GNU GENERAL PUBLIC LICENSE Version 3](LICENSE)