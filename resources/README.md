# Managing resources

To recreate the FEniCS dependency diagram after any modification on easyconfigs, use the following process from the top level directory.

```
eb --robot=easyconfigs --dep-graph=resources/fenics-dolfinx-py-0.9.0-foss-2023b.dot easyconfigs/fenics-dolfinx-py-0.9.0-foss-2023b.eb
dot resources/fenics-dolfinx-py-0.9.0-foss-2023b.dot -Tsvg -o resources/enics-dolfinx-py-0.9.0-foss-2023b.dot
```
