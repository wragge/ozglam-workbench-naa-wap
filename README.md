# OzGLAM data repository workbench
## Series in the National Archives of Australia relating to the White Australia Policy

**Please note this is experimental and unfinished. I'm still learning about the capabilities of Jupyter. Things might change radically!**

This is a collection of [Jupyter](http://jupyter.org/) notebooks to help you explore and use data from the National Archives of Australia relating to the administration of the White Australia Policy. It's part of the bigger [OzGLAM workbench](https://github.com/wragge/ozglam-workbench) project.

This repository includes item-level metadata from 23 series harvested from the National Archives online database RecordSearch. The complete code for harvesting and processing the data is included, as are some examples of how the data can be analysed. The harvested metadata is available as CSV-formatted files (one for each series) in the `RecordSearch/data` directory.

To browse information about the harvested series start with the [summary of all harvested series notebook](https://nbviewer.jupyter.org/github/wragge/ozglam-workbench-naa-wap/blob/master/RecordSearch/Summary%20of%20all%20harvested%20series.ipynb) (this link will open using Jupyter's nbviewer). There you'll find a live version of the table below with links to individual series summaries and visualisations.

[![Screen capture of summary table](https://dl.dropbox.com/s/btfz59wlqii9mrj/naa-wap-series.png)](https://nbviewer.jupyter.org/github/wragge/ozglam-workbench-naa-wap/blob/master/RecordSearch/Summary%20of%20all%20harvested%20series.ipynb)


## Support me

If you think this is a worthwhile endeavour, feel free to [support me on Patreon](https://www.patreon.com/timsherratt).

## Using the workbench

### View on GitHub

You can view the contents on NBViewer or GitHub, but note that these will be static versions so you won't be able to run any of the code.

### Run locally with Jupyter

If you have Jupyter installed, you can clone this repository, and then run Jupyter:

```
git clone https://github.com/wragge/ozglam-workbench-naa-wap.git
cd ozglam-workbench-naa-wap
jupyter notebook
```

### Run online with MyBinder

To use a live version without installing any software, try MyBinder:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wragge/ozglam-workbench-naa-wap/master)

MyBinder launches the notebooks in a custom computing environment with all the software you'll need pre-installed. But note that these environments aren't persistent, so you'll need to make sure you download any data you want to keep.
