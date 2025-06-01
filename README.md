# Active learning for nonadiabatic molecular dynamics

Mikołaj Martyka, Lina Zhang, Fuchun Ge, Yi-Fan Hou, Joanna Jankowska*, Mario Barbatti*, Pavlo O. Dral*. [Charting electronic-state manifolds across molecules with multi-state learning and gap-driven dynamics via efficient and robust active learning](https://doi.org/10.1038/s41524-025-01636-z). *npj Comput. Mater.* **2025**, *11*, 132. DOI: 10.1038/s41524-025-01636-z.
Preprint on ChemRxiv: https://doi.org/10.26434/chemrxiv-2024-dtc1w (2024-08-06).

Code and data
-------------

- Active learning with multi-state ANI, multi-state ANI model, and gapMD are implemented in the open-source [MLatom](https://github.com/dralgroup/mlatom) (version >=3.10). Please see the MLatom page for more details. Links to tutorials are given below.
- All data is available in the above repository, with the exception of the azobenzene training set, which is available at the following DOI: 10.6084/m9.figshare.27024196
- ML models are provided as compressed .npz files, loadable with MLatom version >=3.10.
- Training sets are provided as xz compressed .json molecular databases, compatible with MLatom.

Tutorials
---------

- active learning: https://xacs.xmu.edu.cn/docs/mlatom/tutorial_namd.html#active-learning
- multi-state ANI: https://xacs.xmu.edu.cn/docs/mlatom/tutorial_namd.html#multi-state-ani-models
- gapMD: https://xacs.xmu.edu.cn/docs/mlatom/tutorial_namd.html#gapmd
