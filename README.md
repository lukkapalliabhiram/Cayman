# QuickCalc 🚀 : Sleek 🌟, user-friendly, and smart ad-placement 🎯

QuickCalc is a contemporary and easy-to-use calculator tool 🔧 that offers a sleek and user-friendly experience 👌, with ads strategically positioned to ensure minimal impact on user experience 📱.


*Meridian is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/meridian), or even [use it today](#usage).*


## Usage

To use the Meridian theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/meridian@v0.1.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Meridian will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A brief description of your site's purpose]
```


### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes such as a custom favicon, you can add custom files in your local `_includes` folder. The files provided with the theme provide a starting point and are included by the original layout template.
2. For more extensive changes, copy the original template from the theme's repository<br />(Pro-tip: click "raw" to make copying easier)
3. Create a file called `/_layouts/default.html` in your site
4. Paste the default layout content copied in the first step
5. Customize the layout as you'd like

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was

