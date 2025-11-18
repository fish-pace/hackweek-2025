# Tutorials

Live recordings of the tutorial sessions will be linked here. Some tutorials include
slides, and most have an accompanying Jupyter Notebooks that can be run in our
{{ '[preconfigured software environment]({url})'.format(url=jupyterhub_url) }}
If you are attending the hackweek, you have access to a JupyterHub environment
with all the necessary Python software packages installed that are needed to run
through these tutorials interactively. On the JupyterHub, your home directory persists
so any changes you make to the tutorials will be saved and be there for you next
time you log in.

**How to run the tutorials?** You can either download and upload the tutorials (click download icon) or view the tutorial (click eye icon) and you will see options to open the tutorial in the JupyterHub or Colab. You can also go to the [tutorial GitHub repo](https://github.com/fish-pace/2025-tutorials) and clone that into the JupyterHub.

| Title | Slides | Notebook {{ l1 }} | Notebook {{ d1 }} | Recording | Colab |
| :---- | :----: | :------: | :-------: |  :-------: | :-------:|
| Overview of the JupyterHub                  | [{{ l1 }}][jh-l]      |    |     |  [{{ v0 }}][jh-v]  | |
| Collaborating with Git and GitHub   | [{{ l1 }}][git-l]   |  [{{ l1 }}][git-n]  |     |  [{{ v0 }}][git-v]  |  |
| Accessing PACE data via earthaccess | [{{ l1 }}][ed-l] | [{{ l1 }}][ed-n] | <a href="notebooks/pace_earthdata_access.ipynb" download>{{ d1 }}</a> | [{{ v0 }}][ed-v] |  [{{ c1 }}][ed-c] |
| Remote sensing reflectance (Rrs)  | [{{ l0 }}][rrs-l]   | [{{ l1 }}][rrs-n] |  <a href="notebooks/vizualization_rrs.ipynb" download>{{ d1 }}</a> |  [{{ v0 }}][rrs-v] | [{{ c1 }}][rrs-c] |
| Matchups - points and grids | [{{ l0 }}][mu-l]   | [{{ l0 }}][mu-n] |  [{{ d0 }}][mu-d] |  [{{ v0 }}][mu-v] | |
| Phytoplankton community composition  | [{{ l0 }}][moana-l]   | [{{ l1 }}][moana-n] |  <a href="notebooks/vizualization_moana.ipynb" download>{{ d1 }}</a> |  [{{ v0 }}][moana-v] |  [{{ c1 }}][moana-c] |
| Water classification | [{{ l0 }}][wc-l]   | [{{ l1 }}][wc-n] |  <a href="notebooks/water_classification.ipynb" download>{{ d1 }}</a> |  [{{ v0 }}][wc-v] |  [{{ c1 }}][wc-c] |
| Light attenuation (Kd)  | [{{ l0 }}][kd-l]   | [{{ l1 }}][kd-n] |  <a href="notebooks/kd_vizualization.ipynb" download>{{ d1 }}</a> |  [{{ v0 }}][kd-v] | [{{ c1 }}][kd-c] |
| Simple machine learning - 2D  | [{{ l0 }}][cnn-l]   | [{{ l1 }}][cnn-n] |  <a href="notebooks/CNN_2D.ipynb" download>{{ d1 }}</a> |  [{{ v0 }}][cnn-v] | [{{ c1 }}][cnn-c] |
| Simple machine learning - BRT  | [{{ l0 }}][brt-l]   | [{{ l1 }}][brt-n] |  [{{ d0 }}][brt-d] |  [{{ v0 }}][brt-v] | [{{ c0 }}][brt-c] |

You can find additional Jupyter Notebook tutorials using PACE data on the [NASA Ocean Biology Processing Group website](https://oceancolor.gsfc.nasa.gov/resources/docs/tutorials/), [PACE HackWeek 2024](https://pacehackweek.github.io/pace-2024/) and [PACE HackWeek 2025](https://pacehackweek.github.io/pace-2025/)

[jh-n]: ""
[jh-l]: https://docs.google.com/presentation/d/13hEJXGTW0baH1TtP9GDzpu61HTk8LSipQL8fzF53CZ0/present
[jh-d]: ""
[jh-v]: ""

[git-n]: https://fish-pace.github.io/hackweek-2025/preliminary/git.html
[git-l]: https://docs.google.com/presentation/d/1JuS8pNoq0__TyQMsTcXvvmSO8eaxJkAcxJQIlVpM2XA/present
[git-d]: ""
[git-v]: ""

[ed-n]: notebooks/pace_earthdata_access
[ed-l]: https://docs.google.com/presentation/d/1PKJJ6139McB6WyPb1-z8YnlCjDa6k9jgcdSH3NpEkHc/present
[ed-d]: notebooks/pace_earthdata_access.ipynb
[ed-v]: ""
[ed-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/pace_earthdata_access.ipynb

[rrs-n]: notebooks/vizualization_rrs
[rrs-l]: ""
[rrs-d]: notebooks/vizualization_rrs.ipynb
[rrs-v]: ""
[rrs-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/vizualization_rrs.ipynb

[mu-n]: ""
[mu-l]: ""
[mu-d]: ""
[mu-v]: ""

[moana-n]: notebooks/vizualization_moana
[moana-l]: ""
[moana-d]: notebooks/vizualization_moana.ipynb
[moana-v]: ""
[moana-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/vizualization_moana.ipynb

[wc-n]: notebooks/water_classification
[wc-l]: ""
[wc-d]: notebooks/water_classification.ipynb
[wc-v]: ""
[wc-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/water_classification.ipynb

[kd-n]: notebooks/kd_vizualization
[kd-l]: ""
[kd-d]: notebooks/kd_vizualization.ipynb
[kd-v]: ""
[kd-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/kd_vizualization.ipynb

[cnn-n]: notebooks/CNN_2D
[cnn-l]: ""
[cnn-d]: notebooks/CNN_2D.ipynb
[cnn-v]: ""
[cnn-c]: https://colab.research.google.com/github/fish-pace/2025-tutorials/blob/main/CNN_2D.ipynb

[brt-n]: ""
[brt-l]: ""
[brt-d]: ""
[brt-v]: ""
[brt-c]: ""
