### 1. [CVPR '24] GaussianAvatars: Photorealistic Head Avatars with Rigged 3D Gaussians
**Authors**: Shenhan Qian, Tobias Kirschstein, Liam Schoneveld, Davide Davoli, Simon Giebenhain, Matthias Nießner

<details span>
<summary><b>Abstract</b></summary>
We introduce GaussianAvatars, a new method to create photorealistic head avatars that are fully controllable in terms of expression, pose, and viewpoint. The core idea is a dynamic 3D representation based on 3D Gaussian splats that are rigged to a parametric morphable face model. This combination facilitates photorealistic rendering while allowing for precise animation control via the underlying parametric model, e.g., through expression transfer from a driving sequence or by manually changing the morphable model parameters. We parameterize each splat by a local coordinate frame of a triangle and optimize for explicit displacement offset to obtain a more accurate geometric representation. During avatar reconstruction, we jointly optimize for the morphable model parameters and Gaussian splat parameters in an end-to-end fashion. We demonstrate the animation capabilities of our photorealistic avatar in several challenging scenarios. For instance, we show reenactments from a driving video, where our method outperforms existing works by a significant margin.
</details>

 [📄 Paper](https://arxiv.org/pdf/2312.02069) | [🌐 Project Page](https://shenhanqian.github.io/gaussian-avatars) | [💻 Code](https://github.com/ShenhanQian/GaussianAvatars) | [🎥 Short Presentation](https://youtu.be/lVEY78RwU_I)

### 2. [CVPR '24] SplattingAvatar: Realistic Real-Time Human Avatars with Mesh-Embedded Gaussian Splatting  
**Authors**: Zhijing Shao, Zhaolong Wang, Zhuang Li, Duotun Wang, Xiangru Lin, Yu Zhang, Mingming Fan, Zeyu Wang 
<details span>
<summary><b>Abstract</b></summary>
We present SplattingAvatar, a hybrid 3D representation of photorealistic human avatars with Gaussian Splatting embedded on a triangle mesh, which renders over 300 FPS on a modern GPU and 30 FPS on a mobile device. We disentangle the motion and appearance of a virtual human with explicit mesh geometry and implicit appearance modeling with Gaussian Splatting. The Gaussians are defined by barycentric coordinates and displacement on a triangle mesh as Phong surfaces. We extend lifted optimization to simultaneously optimize the parameters of the Gaussians while walking on the triangle mesh. SplattingAvatar is a hybrid representation of virtual humans where the mesh represents low-frequency motion and surface deformation, while the Gaussians take over the high-frequency geometry and detailed appearance. Unlike existing deformation methods that rely on an MLP-based linear blend skinning (LBS) field for motion, we control the rotation and translation of the Gaussians directly by mesh, which empowers its compatibility with various animation techniques, e.g., skeletal animation, blend shapes, and mesh editing. Trainable from monocular videos for both full-body and head avatars, SplattingAvatar shows state-of-the-art rendering quality across multiple datasets. 
</details>

  [📄 Paper](https://arxiv.org/pdf/2403.05087.pdf) |  [🌐 Project Page](https://initialneil.github.io/SplattingAvatar) | [💻 Code](https://github.com/initialneil/SplattingAvatar)| [🎥 Short Presentation](https://www.youtube.com/watch?v=IzC-fLvdntA)
