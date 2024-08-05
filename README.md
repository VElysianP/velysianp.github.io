## [Hi! My name is Yaoyi!](https://express.adobe.com/page/AeW42ihuUwUTD)

![I am here](IMG_4385.JPG)

Currently, I am a 5th year Ph.D. candidate at UCSB computer science department. 

This is my github resources page. If you are looking for my hoempage: [homepage here](https://express.adobe.com/page/AeW42ihuUwUTD).

## Resources

### Neural Complex Luminaire scene file and mitsuba renderer
This is the renderer code and scene files for the paper: Neural Complex Luminaires: Representation and Rendering. ACM Transactions on Graphics (Proceedings of SIGGRAPH 2021). 

#### Abstract
Complex luminaires, such as grand chandeliers, can be extremely costly to render because the light-emitting sources are typically encased in complex refractive geometry, creating difficult light paths that require many samples to evaluate with Monte Carlo approaches. Previous work has attempted to speed up this process, but the methods are either inaccurate, require the storage of very large lightfields, and/or do not fit well into modern path-tracing frameworks. Inspired by the success of deep networks, which can model complex relationships robustly and be evaluated efficiently, we propose to use a machine learning framework to compress a complex luminaire's lightfield into an implicit neural representation. Our approach can easily plug into conventional renderers, as it works with the standard techniques of path tracing and multiple importance sampling (MIS). Our solution is to train three networks to perform the essential operations for evaluating the complex luminaire at a specific point and view direction, importance sampling a point on the luminaire given a shading location, and blending to determine the transparency of luminaire queries to properly composite them with other scene elements. We perform favorably relative to state-of-the-art approaches and render final images that are close to the high-sample-count reference with only a fraction of the computation and storage costs, with no need to store the original luminaire geometry and materials.

[Repo](https://github.com/VElysianP/Neural_Complex_Luminaire) | [paper](https://dl.acm.org/doi/abs/10.1145/3450626.3459798)


### Precomputed-Dynamic-Appearance-Synthesis-and-Rendering

This is the code for the paper: Precomputed Dynamic Appearance Synthesis and Rendering. EGSR 2024. 

#### Abstract
Interpolation between objects of varying dimensionality is a common task in computer graphics; however, high-quality dynamic natural interpolation for appearance remains scarce. In this paper, we propose a blending framework for general appearances that can be integrated into renderers without modifying the rendering pipeline. For natural interpolation calculations, we use the mathematical tool optimal transport (OT), known for its promising blending quality. Although recent advancements in OT theory have improved computational performance, integrating runtime OT calculations into the path tracing rendering pipeline compromises algorithm efficiency and increases storage requirements. To address this, we propose a novel solution that precomputes appearances into a proxy distribution and introduces a hierarchical query structure. This enables efficient online point or range data querying, allowing for the generation or retrieval of large data sets as needed. Additionally, the proxy and hierarchical query structure facilitate multi-way barycenter computation. With this efficient query structure and barycentric calculation, we demonstrate several applications of our method, including 2D and 3D interpolation, as well as isotropic BRDF interpolation.


[Repo](https://github.com/VElysianP/Precomputed-Dynamic-Appearance-Synthesis-and-Rendering) | [paper](https://diglib.eg.org/items/096e395f-7775-4b9d-800f-e4cd71ea7485) | [EGSR 2024 presentation given by 
Iliyan Georgiev](https://www.youtube.com/watch?v=Qxmiwx9Da2g)
