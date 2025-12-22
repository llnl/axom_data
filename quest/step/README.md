STEP Files
=============

This folder contains example STEP files to be used in conjunction with Axom's `quest::StepFileProcessor` to be converted to `primal` primitives. This permits further processing with other Axom methods, such as `primal`'s 3D GWN methods in `winding_number.hpp`, as demonstrated in the preprint [Robust Containment Queries over Collections of Trimmed NURBS Surfaces via Generalized Winding Numbers](https://arxiv.org/abs/2504.11435).

The following file(s) were created directly within modeling software Rhino3D:
| Filename | Additional Notes |
| -------- | ---------------- |
| boxed_sphere.step | Based on STL example [quest/boxedSphere.stl](https://github.com/LLNL/axom_data/blob/main/quest/boxedSphere.stl) |
| fig4_discretized_surface.step | |
| fig4_original_surface.step | |
| open_cylinder.step | Based on example in [Marussig and Hughes 2017](https://doi.org/10.1007/s11831-017-9220-9) with top face removed |
| revolved_sphere.step | |
| sliced_cylinder.step | Based on example in [Marussig and Hughes 2017](https://doi.org/10.1007/s11831-017-9220-9) |
| tet.step | |

<br/>

The following file(s) were defined directly from Axom primitives 
| Filename | Additional Notes |
| -------- | ---------------- |
| biquintic_sphere_surface.step | Derived with formulas in [Cobb 1988](https://collections.lib.utah.edu/ark:/87278/s61g14n6) |
| teardrop.step | |
| vase.step | Based on example in [Martens and Bessmeltsev 2025](https://doi.org/10.1111/cgf.70194) |

<br/>

The following file(s) are taken from the [ABC dataset](https://doi.org/10.1109/CVPR.2019.00983). Of this collection, many shapes were modified by removing specific surface components to illustrate features of Axom's 3D GWN methods.
| Filename | Additional Notes |
| -------- | ---------------- |
| bearings.step | Index 7963 |
| bobbin.step | Index 933, modified by removing interior and features to expose holes on top face |
| bolt.step | Index 3450 |
| gear.step | Index 9979 |
| joint.step | Index 13, modified by adding trimming curves to front face and removing top patch |
| lamp.step | Index 3800 |
| nut.step | Index 6 |
| pipe.step | Index 9992, modified by removing front face of each opening |
| slide.step | Index 4237 |
| spring_two_patch.step | Index 86, modified by removing caps and performing Bézier extraction on NURBS surfaces |
| spring.step | Index 86, modified by removing caps at each end of cylinder |
| trailer.step | Index 4192, modified by removing bottom face, window faces, and interior details |

<br/>

Miscellaneous
| Filename | Additional Notes |
| -------- | ---------------- |
| connector.step | Bundled with releases of OpenCascade |
| utah_teapot.step | From an archive of [Utah teapot models](https://users.cs.utah.edu/%7Edejohnso/models/teapot.html) |
