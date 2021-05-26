# Description

Mirrored model has its materials flipped inside out when viewed in Autodesk Forge Viewer.
Adding a section plane reverts the mirrored model back to what it should look like.
We are using this [sample viewer](https://github.com/Autodesk-Forge/learn.forge.viewhubmodels/tree/nodejs) from Autodesk.
This weird behavior does not occur when looking at the model in BIM 360 Docs.

# Screenshots

Original model in BIM 360 Docs
![](/screenshots/original_bim_360.png)

Original model in Forge Viewer
![](/screenshots/original_forge_viewer.png)

Mirrored model in BIM 360 Docs
![](/screenshots/mirrored_bim_360.png)

Mirrored model in Forge Viewer
![](/screenshots/mirrored_forge_viewer.png)

Mirrored model in Forge Viewer with section plane
![](/screenshots/mirrored_forge_viewer_section_plane.png)

# Steps to Reproduce

1. Have original file (rac_basic_sample.rvt) containing model elements posted on BIM 360.
2. Create new file (sample_mirrored.rvt) and link original file from BIM 360.
3. Mirror link using Revit tool.
4. Publish new file (sample_mirrored.rvt).
