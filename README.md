My newer Voici test deployment is [here](https://github.com/fomightez/voici-demotestMay24).  
Presently (May 2024), all the notebooks in '`content`' directory were working HERE work in the Voici rendering, **with the exception of `test_file_read.ipynb`**. (That one failing to render in the notebook was due to a known issue at the time for Voici, see [here](https://discourse.jupyter.org/t/bouton-voila-sur-jupyterlite/18505/11?u=fomightez), and there was a workaround for that demonstrated in `test_providing_inside_nb.ipynb`.) When I changed the name to not confilict with my newerr demo, it stopped working. However, the name isn't special as evidenced by [here](https://github.com/fomightez/voici-demotestMay24/tree/main) working and so maybe something about the build is incompatible with something I have here. Or the name is too complex. I haven't sorted it as of yet; however, importantly I moved all of the actual content [here](https://github.com/fomightez/voici-demotestMay24) and Voici works on that site. So it doesn't really matter now that this is broken.

# Voici demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://fomightez.github.io/voici-demotestBASEDonOLDrepo)

[Voici](https://github.com/voila-dashboards/voici) deployed as a static site to GitHub Pages, for demo purposes.

It uses [jupyterlite-xeus-python](https://github.com/jupyterlite/xeus-python-kernel) as a default kernel with a pre-built Emscripten environment.

## ✨ Try it in your browser ✨

https://fomightez.github.io/voici-demotestBASEDonOLDrepo

