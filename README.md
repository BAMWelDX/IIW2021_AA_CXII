# WelDX @ 2021 IIW Annual Assembly Comm. XII meeting

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BAMWelDX/IIW2021_AA_CXII/main?urlpath=lab/tree/iiw2021_CXII_fabry_cagtay_01.ipynb)
[![Documentation](https://readthedocs.org/projects/weldx/badge/?version=v0.4.1)](https://weldx.readthedocs.io/en/latest/)

Repository providing code and datasets accompanying **IIW Doc. XII-2476-2021: WelDX - progress report on the welding
data exchange format**

Talk held online at the 2021 IIW Annual Assembly Comm. XII meeting on 15.07.2021.

### launch on binder

You can launch the notebook for this presentation following this link:\
https://mybinder.org/v2/gh/BAMWelDX/IIW2021_AA_CXII/main?urlpath=lab/tree/iiw2021_CXII_fabry_cagtay_01.ipynb

### links

- WelDX documentation: https://weldx.readthedocs.io/en/latest/
- WelDX GitHub: https://github.com/BAMWelDX/weldx
- WelDX project page: https://www.bam.de/Content/EN/Projects/WelDX/weldx.html

## contents

The example describes a single pass V-Groove weld of 8 mm steel plates.\
All data is stored in the `single_pass_weld.weldx` file.

<video width="600" src="./data/WID417.avi" controls>
  Your browser does not support the video tag.
</video>

Here are the before and after images of the experimental setup:

<img src="./data/WID417_pre.JPG" alt="pre weld image" width=300/> <img src="./data/WID417_post.JPG" alt="post weld image" width=300/>

The interactive notebook demonstrates the contents of the `weldx` file containing the complete dataset and core features
of the `weldx` package.

### file content browsing

Interactively browse and search contents of weldx files.

<img src="./data/view_tree.png" alt="tree view of file contents" width=500/>

### 3D visualization

Create an interactive 3D visualization of the experiment design.

<img src="./data/K3D-1626253607026.png" alt="k3d design viz" width=600/>

And compare it with the real data collected during the experiment.

<img src="./data/K3D-1626253575282.png" alt="k3d experiment viz" width=600/>

### welding groove shapes

Easily create and directly work with welding groove shapes.

<img src="./data/v_groove.png" alt="v-groove shape" width=400/>

### measurements

Store all related measurement data in a single file.

<img src="./data/measurements.png" alt="measurement plots" width=600/>

The measurement chain can be described in detail.

<img src="./data/measurement_chain.png" alt="measurement chain" width=600/>
