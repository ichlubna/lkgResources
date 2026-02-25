3D display by Looking Glass Factory (LKG) is an autostereoscopic device capable of projecting different views of the same scene into different viewing angles. This creates a 3D effect similar to VR or 3D cinema but without additional glasses. The visible 3D parallax serves as a depth cue to human vision. The scene on the display can be focused only at one focusing distance.

[Official website](https://lookingglassfactory.com)

The input data for the display consist of a set of views capturing the scene along a horizontal trajectory. The views are often stored in one image called quilt.
![lkgModel](https://github.com/user-attachments/assets/0f92f1e9-661f-4dd5-9df2-cfb558de5a17)

This is a list of useful resources regarding LKG. The list contains scientific papers, datasets, specialized software with LKG support, tutorials and other relevant resources that might be helpful to people working with LKG. Feel free to create a [pull request](https://github.com/ichlubna/lkgResources/pulls) with additional resources ^_^.

# Datasets
* [Official database of quilts](https://blocks.glass)
* [Experimental datasets used in research](https://www.fit.vut.cz/person/ichlubna/public/random/index.php?section=research#:~:text=Acceleration%20on%20GPU-,3D%20displays,-The%20research%20regarding)
* [Figma quilt template](https://www.figma.com/community/file/1269893384576901841/looking-glass-display-quilt-templates)
* [Looking Glass Demos](https://scanned-reality.com/demo_looking_glass)

# Papers
* [Automatic 3D-display-friendly scene extraction from video sequences and optimal focusing distance identification](https://link.springer.com/article/10.1007/s11042-024-18573-6)
* [How Capturing Camera Trajectory Distortion Affects User Experience on Looking Glass 3D Display](https://link.springer.com/article/10.1007/s11042-023-16350-5)
* [Out-of-focus artifacts mitigation and autofocus methods for 3D displays](https://doi.org/10.1016/j.visinf.2024.12.001)
* [Morphing a Stereogram into Hologram](https://arxiv.org/pdf/1905.01727)
* [54-6: Holographic 3D Telepresence System with Light Field 3D Displays and Depth Cameras over a LAN](https://sid.onlinelibrary.wiley.com/doi/abs/10.1002/sdtp.14794)
* [DataViz3D: An Novel Method Leveraging Online Holographic Modeling for Extensive Dataset Preprocessing and Visualization](https://arxiv.org/abs/2401.10416)
* [An integrated framework for the interaction and 3D visualization of cultural heritage](https://link.springer.com/article/10.1007/s11042-023-14341-0)
* [Advanced Remote Control Using Gesture-Based Teleoperation and Naked-Eye 3D Display](https://www.iroboticsjournal.org/index.php/irobotics/article/view/148)
* [End-to-end system for real-time bidirectional holographic communication](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13034/1303404/End-to-end-system-for-real-time-bidirectional-holographic-communication/10.1117/12.3013045.full)
* [Bringing Video Game Characters into the Real World on a Holographic Light Field Display](https://dl.acm.org/doi/abs/10.1145/3308532.3329423)
* [Exploring Interactive Technology In Education Through The Use Of 3D Lenticular Projection And Volumetric displays](https://rshare.library.torontomu.ca/articles/thesis/Exploring_Interactive_Technology_In_Education_Through_The_Use_Of_3D_Lenticular_Particular_Projection_And_Volumetric_displays/14648649/files/28128867.pdf)
* [Tauray: A Scalable Real-Time Open-Source Path Tracer for Stereo and Light Field Displays](https://dl.acm.org/doi/abs/10.1145/3550340.3564225)
* [Holographic Injection - Master's Thesis about Games Conversion to LKG format](https://www.vut.cz/en/students/final-thesis/detail/136794)
* [DirectL: Efficient Radiance Fields Rendering for 3D Light Field Displays](https://arxiv.org/html/2407.14053v1)
* [Computer-Aided Decision Support and 3D Models in Pancreatic Cancer Surgery: A Pilot Study](https://www.mdpi.com/2077-0383/14/5/1567)
* [Focus-aware compression and image quality metric for 3D displays](https://doi.org/10.1016/j.sigpro.2025.110091)
* [Glasses-Free Holographic Visualization of Pediatric Computed Tomography DICOM Data on Looking Glass 16” OLED](https://ieeexplore.ieee.org/abstract/document/11058832)
* [Interactive Holographic 4D Visualization Multidimensional Structured Grid Data](https://onepetro.org/IPTCONF/proceedings-abstract/20IPTC/20IPTC/D023S129R002/154718)
* [Knowing Your Student: Targeted Teaching Decision Support Through Asymmetric Mixed Reality Collaborative Learning](https://ieeexplore.ieee.org/document/9645428)
* [Using a Portable Autostereoscopic Screen to Improve Anatomy Teaching and Learning](https://www.mdpi.com/2813-0545/2/1/8)
* [3D Visualization of Nanoscale Tomography Using Holographic Displays](https://academic.oup.com/mam/article-abstract/26/S2/1856/6893575?redirectedFrom=PDF)
* [Efficient Rendering for Light Field Displays using Tailored Projective Mappings](https://dl.acm.org/doi/abs/10.1145/3585498)

# Software
* [Official Looking Glass Factory software download page](https://lookingglassfactory.com/software)
* [Official Looking Glass Factory tools source codes](https://github.com/Looking-Glass/Welcome)
* [A tool that converts input quilt image or set of images into the native LKG format](https://github.com/ichlubna/quiltToNative)
* [Experimental scripts for work with LKG data and scene-warping Blender script](https://github.com/ichlubna/lkg)
* [A tool for getting the calibration data form the LKG device](https://github.com/ichlubna/getLKGCalibration)
* [Conversion of computer games to the LKG](https://github.com/jbienz/ReGlass/)
* [Blender LKG addon](https://github.com/regcs/AliceLG)
* [OpenGL 3D renderer for LKG](https://github.com/dormon/3DApps/blob/master/src/renderHoloApps.cpp)
* [OpenGL renderer of quilts with refocusing](https://github.com/dormon/3DApps/blob/master/src/renderHoloFocus.cpp)
* [Experimental LKG snippets](https://github.com/lonetech/LookingGlass/tree/master)
* [Online demo scenes on ShaderToy](https://www.shadertoy.com/results?query=looking+glass)
* [Looking Glass quilts from side tracking shots in Adobe After Effects](https://github.com/JuanIrache/looking-glass-after-effects)
* [Looking Glass Web applications](https://stereo.jpn.org/lkg/indexe.html)
* [Real-time video to hologram generation](https://github.com/vossr/Real-time-hologram-generation)
* [Holographic LKG Matrix code](https://github.com/Rezmason/matrix/)
* [Displaying 3d genomic data using webgl on LKG](https://github.com/flatironinstitute/looking_glass_3d_test)
* [Virtual Pokemon on LKG](https://github.com/IdreesInc/Holographic-Porygon?tab=readme-ov-file)
* [Experimental LKG support for Doom game Engine](https://github.com/shole/gzdoom)
* [3D Gaussian Splat Viewer for Looking Glass](https://github.com/chrisirhc/looking-glass-viewer-experiments)
* [Interacting with the Looking Glass Holoplay Service in JavaScript](https://github.com/chigozienri/holoplayjs-examples)
* [HoloMusicViz: Spotify Visualizer for LKG](https://github.com/8ude/spotify-viz)
* [HoloWeasel: Looking Glass and Three.js working example files](https://github.com/sneakyweasel/HoloWeasel)
* [Rou Hun Fan's port of the Whitestone demo for LKG](https://github.com/flowen/looking-glas-factory-demo)

# Tutorials
* [How to create holograms for Looking Glass (quilt format) from a video captured with a phone](https://volurama.com/howto_create_looking_glass_quilt.html)
* [Lightfield capture to Looking Glass “Quilt” image, scripted on the command line](https://www.summet.com/blog/2022/08/16/lightfield-capture-to-looking-glass-quilt-image-scripted-on-the-command-line/)

# Similar Devices
* [Leia Lume Pad 3D Tablet](https://www.leiainc.com/lume-pad-2)
* [Voxon Volumetric Display](https://www.voxon.co)
* [Red Hydrogen One 3D Phone](https://en.wikipedia.org/wiki/Red_Hydrogen_One)
* [Holovect](https://www.kickstarter.com/projects/2029950924/holovect-holographic-vector-display)
* [CREAL Light Field Glasses](https://creal.com)

# Others
* [Patents](https://patents.justia.com/assignee/looking-glass-factory-inc)
