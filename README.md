# Hugo-Programmer
A sleek and minimal theme for [Hugo](https://gohugo.io).
*This theme is a modified version of the [Hugo Coder](https://themes.gohugo.io/themes/hugo-coder/) theme.*

# Example Site
Can't decide if you like it or not? You can find a [live demo](https://tanishkthoria.netlify.app) of this theme. 

# How to get started
1) This theme should be added as a submodule in your themes directory:
  ```
  git submodule add https://github.com/TanishkThoria/Hugo-Programmer.git themes/Hugo-Programmer
  ```


2) Edit your ```config.toml``` file to match the new theme. You can either do this by:
  - Simply adding  ```theme = "Hugo-Programmer"``` at the top of the file and then adding other parameters seperately.

  - Or by copying this [baseline configuration]() and filling it out.
    **This is the recommended option due to it having the most reability**

  - Or by copying and editing the [example website](https://github.com/TanishkThoria/Personal-Website/blob/main/config.toml).
    *Note that some of the images in the example website may not load properly in your website due to them being relatve links.*
    *This could be fixed by either locally downloading the same images or adding*
    ```https://tanishkthoria.netlify.app/```
    *in front of all relative links.*

3) You should be good to go! To display the current version of the website *including drafts**, execute the following command:
  ```
  hugo server -D
  ```
  or just ```hugo server``` if you do not want to display drafts (This is how the website would look like if published).

  the resulting site will be displayed at ```http://localhost:1313/```

  *drafts of blog posts

# Modifications
Wonder what is different from the original Hugo-Coder theme?

This theme:
- Supports custom images for socials (non-Font Awesome)
- Added socials to footer
- More attractive blog posts page
	- Supports image thumbnails
	- Categorizations shown when in list-view
	- Descriptions shown when in list-view

# Need help?
Documentation can be found under the ```[docs](https://github.com/TanishkThoria/Hugo-Programmer/tree/main/docs)``` folder.

Feature requests and issues can be reported through [Github's Issues](https://github.com/TanishkThoria/Hugo-Programmer/issues)

Further questions can be email to me at tanishkthoria@gmail.com 

# Licensing
This theme, as well as the theme is forked from, is licensed under the [MIT License](https://github.com/TanishkThoria/Hugo-Programmer/blob/main/LICENSE)

# Have a great day :)
