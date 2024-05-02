---
title: CT Volume Rendering in Mixed Reality
date: 2023-12-02
summary: ""

# Cover image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  #caption: "Caption text"
  focal_point: "top"
  preview_only: false

tags: [funded]

authors:
  - admin

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

---

Medical volumetric data, like CT or MRT scanners produce, are commonly viewed in 2D slices on screens. However, it is possible to display this volumetric data in 3D via direct volume rendering. This improves the user's ability to understand the data in a 3D context, aids in understanding depth and explorability, and allows less experienced users to better understand the displayed data. Volumetric path tracing renders highly realistic images, possibly with accurate lighting and shadows, depth of field, etc., making small details, object order, and occlusions more easily visible.

It is interesting to use immersive 3D display hardware, like Virtual or Augmented Reality headsets to fully use advanced volumetric visualization techniques advantages. With these head-mounted displays, more investigation into interaction metaphors is needed in the context of volume rendering. While controller-based interaction is commonly used, especially for explorative analysis, direct manipulation could improve the status quo. Using one's hands or haptic interaction with 3D-printed volumes could aid in detecting abnormalities [1]. With VR and tracking devices, it is now possible to see the scans and anatomical conditions on the user's body instead of free-floating. While this could help aid understanding and create awareness for specific medical conditions, it might also have negative consequences. The impact of potentially disturbing medical conditions on one's body has not been extensively researched. In a preliminary work, however, we found no adverse effects of minor injuries or anatomical avatars when embodied by participants [2]. Using state-of-the-art AI methods, we further investigated creating reconstructed environments from simple phone camera videos. Such reconstructions can be used for medical planning [3] and provide an environment for in-context learning.

Future works in this research will focus on bringing such visualizations to a broader set of devices via optimizations and intermediate representations like Gaussian Splatting. Further research into the interaction affordances of such rendered anatomies is also planned. Using a game engine as a development platform allows us to look deeper into the affordances of cross-virtuality visualization, enabling a variety of mixed-reality and handheld devices to explore the same anatomy collaboratively

{{< figure src="Constantin/slicingvolume.png">}}

{{< figure src="Constantin/spatialPlanning.png">}}

{{< figure src="Constantin/volumeRendering.png">}}


[1] C. Kleinbeck et al., „Adaptive Volumetric Anatomy Visualization in VR with Tangible Control“, in 2023 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct), Sydney, Australia: IEEE, Oct. 2023, S. 613–614. doi: 10.1109/ISMAR-Adjunct60411.2023.00131.

[2] C. Kleinbeck, H. Schieber, J. Kreimeier, A. Martin-Gomez, M. Unberath, and D. Roth, „Injured Avatars: The Impact of Embodied Anatomies and Virtual Injuries on Well-being and Performance“, IEEE Trans. Visual. Comput. Graphics, S. 1–11, 2023, doi: 10.1109/TVCG.2023.3320224.

[3] C. Kleinbeck, H. Zhang, B. Killeen, D. Roth, M. Unberath, Neural Digital Twins: Reconstructing Complex Medical Environments for Spatial Planning in Virtual Reality. IJCARS 2024

Constantin is supported by a scholarship from Siemens Healthineers and the Digital Health Innovation Platform (d.hip). Thank you!


{{< figure src="Constantin/scholarship.png">}}
