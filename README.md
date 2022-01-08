# :pizza: pizzarobotics.org - [![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

# Run locally

If you have **docker** and **docker-compose** you can use only this command

```
docker-compose up -d
```

**Note:** If you are updating `config.yml` or `_config.dev.yml` please **restart** container.

# Install ruby and run on your host

If you want install all environment on your desktop you need to install **ruby**:

https://gorails.com/setup/ubuntu/20.04#ruby-rbenv
* Using rbenv
* version 2.7.3

When is done, please run:

```
bundle
```

to run on your local machine, please execute:

```
rake serve
```

eq of: `bundle exec jekyll serve --config _config.yml,_config.dev.yml --incremental --livereload`

### Theme reference

* https://mmistakes.github.io/minimal-mistakes/
* https://github.com/mmistakes/mm-github-pages-starter
* https://ptc-it.de/enabling-cookie-consent-with-jekyll-minimal-mistakes/
* https://ptc-it.de/add-favicon-to-mm-jekyll-site/
* https://www.aleksandrhovhannisyan.com/blog/how-to-add-a-copy-to-clipboard-button-to-your-jekyll-blog/
* Make a table from csv file https://jekyllrb.com/tutorials/csv-to-table/

# Other
* https://emojipedia.org/
* https://realfavicongenerator.net/
* https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/3d-file-viewer

# License

This project is under license [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg