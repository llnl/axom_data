STEP Files
=============

This folder contains example STEP files to be used in conjunction with Axom's `quest::StepFileProcessor` to be converted to `primal` primitives. This permits further processing with other Axom methods, such as `primal`'s 3D GWN methods in `winding_number.hpp`, as demonstrated in the preprint [Robust Containment Queries over Collections of Trimmed NURBS Surfaces via Generalized Winding Numbers]{https://arxiv.org/abs/2504.11435}.

The following file(s) were created directly within modeling software Rhino3D:
- boxed_sphere.step (based on STL example [quest/boxedSphere.stl]{https://github.com/LLNL/axom_data/blob/main/quest/boxedSphere.stl})
- fig4_discretized_surface.step
- fig4_original_surface.step
- open_cylinder.step (based on example in [Marussig and Hughes 2017]{https://doi.org/10.1007/s11831-017-9220-9})
- revolved_sphere.step
- sliced_cylinder.step (based on example in [Marussig and Hughes 2017]{https://doi.org/10.1007/s11831-017-9220-9})
- tet.step

The following file(s) were defined directly from Axom primitives 
- biquintic_sphere_surface.step (derived with formulas in [Cobb 1988]{https://collections.lib.utah.edu/ark:/87278/s61g14n6})
- teardrop.step
- vase.step (based on example in [Martens and Bessmeltsev 2025]{https://doi.org/10.1111/cgf.70194})

The following file(s) are bundled with releases of OpenCascade
- connector.step

The following file(s) are taken from an archive of [Utah teapot models]{https://users.cs.utah.edu/%7Edejohnso/models/teapot.html}
- utah_teapot.step

The following file(s) are taken from the [ABC dataset]{https://doi.org/10.1109/CVPR.2019.00983}. Of this collection, many shapes were modified by removing specific surface components to illustrate features of Axom's 3D GWN methods.
- bearings.step (index 7963)
- bobbin.step (index 933, modified by removing interior and features to expose holes on top face)
- bolt.step (index 3450)
- gear.step (index 9979)
- joint.step (index 13, modified by adding trimming curves to front face and removing top patch)
- lamp.step (index 3800)
- nut.step
- pipe.step (index 9992, modified by removing front face of each opening)
- slide.step (index 4237)
- spring_two_patch.step (index 86, modified by removing caps and performing Be'zier extraction on NURBS surfaces)
- spring.step (index 86, modified by removing caps at each end of cylinder)
- trailer.step (index 4192, modified by removing bottom face, window faces, and interior details)