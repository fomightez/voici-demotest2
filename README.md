My newer Voici test deployment is [here](https://github.com/fomightez/voici-demotestMay24).  
Presently (May 2024), all the notebooks in '`content`' directory HERE were working in the Voici rendering, **with the exception of `test_file_read.ipynb`**. (That one failing to render in the notebook was due to a known issue at the time for Voici, see [here](https://discourse.jupyter.org/t/bouton-voila-sur-jupyterlite/18505/11?u=fomightez), and there was a workaround for that demonstrated in `test_providing_inside_nb.ipynb`.) When I changed the name to not conflict with my newer demo, it stopped working. I think when it build and deployed it didn't work as it did back then. So I updated settings in `build-environment.yml` under `pip` and then it alsmost works but hangs on `Running...` in Voici render whether I use settings from four months ago or now However, it just did a 404 when I had earlier settings there and so that is at least better. What is causing it to stick on 'Running...'. I have no idea since the newer version I made with the current template works. But maybe besides this there is some other difference I cannot determinine with quick view like I've been doing. Importantly, I moved all of the actual content [here](https://github.com/fomightez/voici-demotestMay24) and Voici works on that site. And so it doesn't really matter now that this is broken.

# Voici demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://fomightez.github.io/voici-demotestBASEDonOLDrepo)

[Voici](https://github.com/voila-dashboards/voici) deployed as a static site to GitHub Pages, for demo purposes.

It uses [jupyterlite-xeus-python](https://github.com/jupyterlite/xeus-python-kernel) as a default kernel with a pre-built Emscripten environment.

## ✨ Try it in your browser ✨

https://fomightez.github.io/voici-demotestBASEDonOLDrepo

