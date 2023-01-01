# Quick Start

To start using `Hugo-Programmer`:

1) This theme should be added as a submodule in your themes directory:
  ```
  git submodule add https://github.com/TanishkThoria/Hugo-Programmer.git themes/Hugo-Programmer
  ```
<br/>

2) Edit your ```config.toml``` file to match the new theme. You can do this by:

  - Simply adding  ```theme = "Hugo-Programmer"``` at the top of the file and then adding other parameters seperately.

  - Or by copying this [baseline configuration](https://github.com/TanishkThoria/Hugo-Programmer/blob/main/docs/configurations.md#complete-example) and filling it out. <br/>
    **This is the recommended option due to being mostly filled out**

  - Or by copying and editing the [example website](https://github.com/TanishkThoria/Personal-Website/blob/main/config.toml). <br/>
    *Note that some of the images in the example website may not load properly in your website due to them being relative links.*
    *This could be fixed by either locally downloading the same images or adding*
    ```https://tanishkthoria.netlify.app/```
    *in front of all relative links.*


3) You should be good to go! To display the current version of the website *including drafts**, execute the following command:
  ```
  hugo server -D
  ```
  or just ```hugo server``` if you do not want to display drafts (This is how the website would look like if published).

  The resulting site will be displayed at ```http://localhost:1313/```

  *drafts of blog posts

