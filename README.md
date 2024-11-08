<div align="center">


<font size=4>   </font>
    <h1>3dmicrofeel 😊: TEAM OVERVIEW</h1>
</div>


<br>

**Microfeel** is an interdisciplinary team with excellent overseas PhD academic background. We have been deeply engaged in the fields of spatial automatic generation and spatial understanding, artificial intelligence and machine learning for many years. We are the earliest group of researchers and practitioners to conduct AI3D.

---
## Ximing Zhong(CEO)

1.**[Building-VGAE Generating 3D detailing and layered building models from simple geometry](https://www.researchgate.net/publication/384081421_Building-VGAE_Generating_3D_detailing_and_layered_building_models_from_simple_geometry)**

**Jiadong Liang,Ximing Zhong,Immanuel Koh**

*Abstract*

In the current field of AI-assisted architectural design, deep learning models primarily focus on simulating the highly detailed final models designed by human architects. However, in practical design tasks, the final model demands a high level of detail and clear layered classification information for building components. This presents a more significant challenge. We propose a three-dimensional(3D) building generation framework-Building-VGAE, based on Variational Graph Autoencoder (VGAE). Building-VGAE can generate 3D models with detailed building components and layered structure information from end to end, according to design constraints and building volumes. Building-VGAE's experiment involves transforming 27,965 Housegan data into 3D data represented as graph-structured. The VGAE model then learns the data features and predicts the building component categories to which nodes and edges belong in the experiment. The results demonstrate that the framework can precisely reconstruct and predict building layouts that comply with design constraints and enable unified editing of building components of the same category. Building-VGAE contributes to its ability to learn the generative relationship from design constraints and building volumes to complex high-detail models compared to existing AI generative models. It also possesses prediction and editing capabilities based on the layered classification information of building components. This framework has the potential to position AI as a design partner for human architects, offering end-to-end 3D generative intelligence.

2.**[A FRAMEWORK FOR FINE-TUNING URBAN GANS USING DESIGN DECISION DATA GENERATED BY ARCHITECTS THROUGH GANS APPLICATIONS](https://research.aalto.fi/en/publications/a-framework-for-fine-tuning-urban-gans-using-design-decision-data)**

**Ximing Zhong, Jiadong Liang, Pia Fricker, Shengyu Liu**

*Abstract*

Recent studies have utilized Generative Adversarial Networks (GANs) to learn from existing urban layouts for urban design tasks. We define these GANs as Urban-GAN. However, urban layouts generated by Urban-GAN lack specificity and often require multiple modifications by architects to meet specific design requirements, making the process inefficient and non-customizable. Inspired by the concept of fine-tuning language models, we propose a stacked GAN model framework that fine-tunes Urban-GAN using data generated by architects in solving specific design tasks, forming AD-Urban-GAN. Our results indicate that layouts produced by AD-Urban-GAN more effectively emulate architects' design morphology decisions, enhancing Urban-GAN’s adaptability and efficiency in handling design tasks. Furthermore, AD-Urban-GAN enhances the customizability of Urban-GAN models for specific urban design tasks, generating layouts that accurately understand and meet the requirements of specific tasks. AD Urban-GAN significantly streamlines the process of generating design prototypes for specific task types, enabling precise quantitative control over urban layout results. This workflow establishes a data acquisition and training loop that strengthens the customizability of existing GANs. The design decision data generated by architects can improve the adaptability and customization of GANs models, facilitating efficient collaborative work between architects and artificial intelligence.

3.**[AI as a Collaborative Partner in Landscape Form-finding](https://research.aalto.fi/en/publications/ai-as-a-collaborative-partner-in-landscape-form-finding)**

**Chuheng Tan, Ximing Zhong, Prof. Dr. Pia Fricker**

*Abstract*

This study introduces an AI-assisted workflow for wind simulation in landscape form-finding. It can rapidly deliver a series of design options within designers' predefined constraints, each detailed with wind indicators. Integrating AI to detect subtle environmental changes and align with designers' intuitive decisions, this research fosters a collaborative paradigm between landscape architects and AI, aiming to shift from physics engine simulations to employing real-time AI simulations for rapidly aiding designers in the form-finding process in landscape design.

4.**[BRIDGING BIM AND AI: A Graph-BIM Encoding Approach For Detailed 3D Layout Generation Using Variational Graph Autoencoder](https://research.aalto.fi/en/publications/bridging-bim-and-ai-a-graph-bim-encoding-approach-for-detailed-3d)**

**Jiadong Liang, Ximing Zhong, Immanuel Koh**

*Abstract*

Building Information Modelling (BIM) data provides an abundant source with hierarchical and detailed information on architectural elements. Nevertheless, transforming BIM data into an understandable format for AI to learn and generate controllable and detailed three-dimensional (3D) models remains a significant research challenge. This paper explores an encoding approach for converting BIM data into graph-structured data for AI to learn 3D models, which we define as Graph-BIM encoding. We employ the graph reconstruction capabilities of a Variational Graph Autoencoder (VGAE) for the unsupervised learning of BIM data to identify a suitable encoding method. vGaE's graph generation capabilities also reason for spatial layouts. Results demonstrate that VGAE can reconstruct BIM 3D models with high accuracy, and can reason the entire spatial layout from partial layout information detailed with architectural components. The primary contribution of this research is to provide a novel encoding approach for bridging AI and BIM encoding. The Graph-BIM encoding method enables low-cost, self-supervised learning of diverse BIM data, capable of learning and understanding the complex relationships between architectural elements. Graph-BIM provides foundational encoding for training general-purpose AI models for 3D generation.

5.**[A Human–Machine Collaborative Building Spatial Layout Workflow Based on Spatial Adjacency Simulation](https://research.aalto.fi/en/publications/a-humanmachine-collaborative-building-spatial-layout-workflow-bas)**

**Ximing Zhong, Fujia Yu, Beichen Xu**

*Abstract*

The space layout of a reasonable modular building prototype is a time consuming and complex process. Many studies have optimised automatic spatial layouts based on spatial adjacency simulation. Although machine-produced plans satisfy the adjacency and area constraints, people still need further manual modifications to meet other spatially complex design requirements. Motivated by this, we provide a human–machine collaborative design workflow that simulates the spatial adjacency relationship based on physical models. Compared with previous works, our workflow enhances the automated space layout process by allowing designers to use environment anchors to make decisions in automatic layout iterations. A case study is proposed to demonstrate that the solution generated by our workflow can initially complete different customised design tasks. The workflow combines the advantages of the designer's decision-making experience in manual modelling with the machine's ability in rapid automated layout. In the future, it has the potential to be developed into a designer-machine collaboration tool for completing complex building design tasks.

6.**[A Rapid Wind Velocity Prediction Method in Built Environment Based on CycleGAN Model](https://research.aalto.fi/en/publications/a-rapid-wind-velocity-prediction-method-in-built-environment-base)**

**Chuheng Tan, Ximing Zhong**

*Abstract*

Although the wind microclimate and wind environment play important roles in urban prediction, the time-consuming and complicated setup and process of wind simulation are widely regarded as challenges. There are several methods to use deep learning (DL) models for wind speed prediction by labeling pairs of wind simulation dataset samples. However, many wind simulation experiments are needed to obtain paired datasets, which is still time-consuming and cumbersome. Compared with previous studies, we propose a method to train a DL model without labelling paired data, which is based on Cycle Generative Adversarial Network (cycleGAN). To verify our hypothesis, we evaluate the results and process of the pix2pix model (requires paired datasets) and cycleGAN (does not requires paired datasets), and explore the difference of results between these two DL models and professional CFD software. The result shows that cycleGAN can perform as well as pix2pix in accuracy, indicating that some random city plans image samples and random wind simulation samples can train surrogate models as accurate as labelled DL methods. Although the DL method has similar results to the professional CFD method, the details of the wind flow results still need improvement. This study can help designers and policymakers to make informed decisions to choose Dl methods for real-time wind speed prediction for early-stage design exploration.


7.**[Building-GNN: Exploring a co-design framework for generating controllable 3D building prototypes by graph and recurrent neural networks](https://research.aalto.fi/en/publications/building-gnn-exploring-a-co-design-framework-for-generating-contr)**

**Ximing Zhong, Immanuel Koh, Prof. Dr. Pia Fricker**

*Abstract*

This paper discusses a novel deep learning (DL）framework named Building-GNN, which combines the Graph Neural Network (GNN) and the Recurrent neural network (RNN) to address the challenge of generating a controllable 3D voxel building model. The aim is to enable architects and AI to jointly explore the shape and internal spatial planning of 3D building models, forming a co-design paradigm. While the 3D results of previous DL methods, such as 3DGAN, are challenging to control in detail and meet the constraints and preferences of architects' inputs, Building-GNN allows for reasoning about the complex constraint relationships between each voxel. In Building-GNN, the GNN simulates and learns the graph structure relationship between 3D voxels, and the RNN captures the complex interplaying constraint relationships between voxels. The training set consists of 4000 rule-based generated 3D voxel models labeled with different degrees of masking. The quality of the 3D results is evaluated using metrics such as IoU, Fid, and constraint satisfaction. The results demonstrate that adding RNN enhances the accuracy of 3D model shape and voxel relationship prediction. Building-GNN can perform multi-step rational reasoning to complete the 3D model layout planning in different scenarios based on the architect's precise control and incomplete input.

8.**[A Discussion on an Urban Layout Workflow Utilizing Generative Adversarial Network (GAN) - With a focus on automatized labeling and dataset acquisition](https://research.aalto.fi/en/publications/a-discussion-on-an-urban-layout-workflow-utilizing-generative-adv)**

**Ximing Zhong, Pia Fricker, Fujia Yu, Chuheng Tan, Yuzhe Pan**

*Abstract*

Deep Learning (DL) has recently gained widespread attention in the automation of urban layout processes. This study proposes a rule-based and Generative Adversarial Network (GAN) workflow to automatically select and label urban datasets to train customized GAN models for the generation of urban layout proposals. The developed workflow automatically collects and labels urban typology samples from open-source maps. Furthermore, it controls the results of the GAN process with labels and provides real-time urban layout suggestions based on a co-design process. The conducted case study shows that the average value of the GAN results, trained from an automatically generated dataset, meets the site's requirements. The developed co-design strategy allows the architect to control the GAN process and perform iterations on urban layouts. The research addresses the research gap in GAN applications in the field of urban design and planning. Many studies have demonstrated that training the (GAN) model by labeling enables machines to learn urban morphological features and urban layout logic. However, two research gaps remain: (1) The manual filtering of GAN urban sample datasets to fit site-specific design requirements is very time-consuming. (2) Without a suitable data labeling method, it is difficult to manage the GAN process in such a manner to facilitate the meeting of overriding design requirements.

9.**[GaussianSpace: Text guide 3D Gaussian](https://gaussianspace.github.io/)**

**Shengyu Meng, Ximing Zhong, Fujia Yu**

*Abstract*

Integrating 2D diffusion models with 3D Gaussian splatting for text-guided generation of individual 3D objects and editing Gaussian scenes are recently receiving increasing attention. However, current methods for single object generation normally require additional constraints, such as masks and normal maps, which limit their applicability in handling complex spaces. Furthermore, current techniques for text-guided 3D Gaussian editing typically rely on Iterative Dataset Update (IDU) methods based on the instruct nerf2nerf, which are also unsuitable for large spatial manipulations. In response to these challenges, we propose a new method, GaussianSpace, which enables effective text-guided editing of large space in 3D Gaussian Splatting. The key innovation of this method lies in its consideration of both RGB loss from the ground-true images and Score Distillation Sampling (SDS) loss based on the diffusion model during the iterative process. Additionally, we have introduced an automatic weighted loss technique to steadily descend the overall loss, ensuring that the edited Gaussian scene adapts to text instructions while retaining its original structural features. This marks the first successful implementation of text-guided 3D Gaussian large spatial manipulations.

## Fujia Yu

1.**[An Interactive Visual System for Generating Striking Pseudo Base Stations Decisions](https://researchportal.tuni.fi/en/publications/an-interactive-visual-system-for-generating-striking-pseudo-base-)**

**Fujia Yu**

*Abstract*

The Pseudo base stations cause a great number of social and economic security problems with spreading spam messages. However, it is a serious challenge for security department to recognize the behavior patterns of pseudo base stations, then make use of limited police resources to prevent their activities and even to arrest related criminals. In this paper, a novel visual analytic approach to reveal the spatial-temporal behavior patterns of pseudo base stations is presented. In this approach, it takes advantage of density clustering over high frequency positions, and curve fitting on each cluster. This system supports decision makers to formulate patrol routes on the basis of above approximate trajectory. This approach has been demonstrated effective by means of case studies of authority data and has been evaluated novel and valuable in the view of domain experts.

2.**Leveraging Large Language Models and AI Agents for Dynamic Content Generation in Video Games (to be published)**

**Fujia Yu, Ximing Zhong**

*Abstract*

This study explores the application of large language models and AI agents to dynamically generate content in video games, creating responsive and adaptive player-driven experiences. By integrating AI, games can evolve in response to player actions, generating unique narratives and scenarios without the need for extensive manual scripting. The results showcase how AI-powered content generation can reduce development time while enhancing gameplay variety and immersion.

3.**AI-Enhanced NPC Interaction: Utilizing AI Agents for Realistic and Adaptive Non-Player Character Behaviors (to be published)**

**Fujia Yu, Ximing Zhong, Yingkai Li** 

*Abstract*

This paper examines the use of AI agents to produce realistic and adaptive behaviors in non-player characters (NPCs). AI agents empower NPCs to respond intelligently to player choices, enabling more nuanced and immersive interactions. The study demonstrates that AI-enhanced NPC behavior can significantly improve player engagement by providing dynamic and context-sensitive responses within the game world.

4.**Dynamic Story Generation: Integrating User Inputs and In-Game Environments for Immersive Narratives (to be published)**

**Fujia Yu, Ximing Zhong** 

*Abstract*

This paper proposes a dynamic storytelling framework that integrates player inputs and environmental data to generate immersive, personalized narratives. The system leverages AI algorithms to adapt story progression based on player interactions, creating unique experiences with each playthrough. Case studies reveal that such adaptive storytelling fosters deeper engagement and allows players to feel more involved in the story.

5.**Intelligent Resource Management: AI Agents and Their Role in Managing Game Resources and Ecologies (to be published)**

**Fujia Yu, Ximing Zhong, Yingkai Li**

*Abstract*

The study investigates AI agents in managing in-game resources and ecosystems to create balanced, self-sustaining game worlds. By controlling resource allocation and ecological dynamics, AI agents ensure players face strategic challenges while maintaining in-game equilibrium. This approach offers a scalable solution to resource management, enhancing both gameplay complexity and realism.

6.**Scaling Game Systems: The Impact of AI on Dynamic Resource Allocation and Gameplay Adaptation (to be published)**

**Fujia Yu, Ximing Zhong** 

*Abstract*

This paper discusses AI's role in enabling scalable game systems through dynamic resource allocation and gameplay adaptation. By adjusting resources and adapting game mechanics in real-time, AI allows games to scale with player actions, providing a more responsive experience. The findings show that AI-driven adaptability leads to more engaging, varied gameplay.

7.**Harnessing Multimodal Inputs and RAG Technology for Enhanced Game Interaction and Content Creation (to be published)**

**Fujia Yu, Ximing Zhong, Yingkai Li** 

*Abstract*

This paper presents an interactive framework using multimodal inputs and Retrieval-Augmented Generation (RAG) technology to enhance game interaction and content creation. This approach allows players to interact with the game world more fluidly through various input forms, creating a more seamless and immersive experience. The framework has been evaluated as an effective tool for both players and developers in creating adaptive, rich game content.

8.**Designing Player-Centric Games: AI Approaches for Personalized and Immersive Gameplay (to be published)**

**Fujia Yu, Ximing Zhong** 

*Abstract*

The study outlines AI-driven approaches to create personalized, immersive gameplay experiences centered around player preferences. AI models adapt game dynamics to individual player choices and behaviors, leading to a tailored experience that enhances player engagement. Results indicate that AI-based personalization can foster a deeper connection between the player and the game world.

9.**MMGSG: A Multimodal Multi-agent Game Systems Generation Framework (to be published)**

**Fujia Yu, Ximing Zhong, Yingkai Li**

*Abstract*

This paper introduces the Multimodal Multi-agent Game Systems Generation (MMGSG) framework, designed to create complex, multimodal interactive game systems. Leveraging AI agents and multimodal inputs, MMGSG facilitates the creation of intricate game environments with dynamic agent interactions. The framework has been evaluated as a versatile tool for generating engaging, adaptive game systems suitable for a variety of genres.

## Zixun Huang

1.**[Robust Digital-Twin Localization via An RGBD.based Transformer Network and AComprehensive Evaluation on a Mobile Datase](https://github.com/augcog/DTTD2)**

**Huang, Z, Yao, K  Zhao S, Pan C, Xu T, Feng, W, Yang A**

2.**[MARL: Multi-scale Archetype Representation Learning for Urban Building Energy Modeling](https://openaccess.thecvf.com/content/ICCV2023W/CVAAD/html/Zhuang_MARL_Multi-scale_Archetype_Representation_Learning_for_Urban_Building_Energy_Modeling_ICCVW_2023_paper.html)**

**Zhuang, X, Huang, Z, Zeng W, Caldas, L.**

*Abstract*

Building archetypes, representative models of building stock, are crucial for precise energy simulations in Urban Building Energy Modeling. The current widely adopted building archetypes are developed on a nationwide scale, potentially neglecting the impact of local buildings' geometric specificities. We present Multi-scale Archetype Representation Learning (MARL), an approach that leverages representation learning to extract geometric features from a specific building stock. Built upon VQ-AE, MARL encodes building footprints and purifies geometric information into latent vectors constrained by multiple architectural downstream tasks. These tailored representations are proven valuable for further clustering and building energy modeling. The advantages of our algorithm are its adaptability with respect to the different building footprint sizes, the ability for automatic generation across multi-scale regions, and the preservation of geometric features across neighborhoods and local ecologies. In our study spanning five regions in LA County, we show MARL surpasses both conventional and VQ-AE extracted archetypes in performance. Results demonstrate that geometric feature embeddings significantly improve the accuracy and reliability of energy consumption estimates.

3.**[Encoding Urban Ecologies: Automated Building Archetype Generation through Self.Supervised Learning for Energy Modeling](https://arxiv.org/abs/2404.07435)**

**Zhuang,X, Huang, Z, Zeng W, Caldas, L.**

## Shengyu Meng

1.**[Exploring in the latent space of design: A method of plausible building facades images generation, properties control and model explanation base on StyleGAN2](https://scholar.googleusercontent.com/scholar?q=cache:a_lglX1T5csJ:scholar.google.com/+Exploring+in+the+Latent+Space+of+Design:A+Method+of+Plausible+Building+Facades+lmages+&hl=en&as_sdt=0,5)**

**Shengyu Meng**

*Abstract*

GAN has been widely applied in the research of architectural image generation. However, the quality and controllability of generated images, and the interpretability of model are still potential to be improved. In this paper, by imple menting StyleGAN2 model, plausible building façade images could be generated without conditional input. In addition, by applying GANSpace to analysis the latent space, high-level properties could be controlled for both generated images and novel images outside of training set. At last, the generating and controlling process could be visualized with image embedding and PCA projection method, which could achieve unsupervised classification of generated images, and help to understand the correlation between the images and their latent vectors.

## Xuhui Lin

1.**[RESHAPE Rapid forming and simulation system using unmanned aerial vehicles foarchitectural representation.](https://discovery.ucl.ac.uk/id/eprint/10178065/)**

**Lin, X, Rizal M**

*Abstract*

As digital technology advances, multiple ways of repre-senting objects interactively in space, architects and designers begin to use Virtual Reality (VR) and Immersive Digital Environ-ments (IDE) to communicate their ideas. However, these technolo-gies are bounded with their spatial limitations. In responding to this issue, our paper introduces ReShape, a digital-physical spatial representation system supported by Unmanned Aerial Vehicle (UAV) swarm technology that allows a user to project their unbuilt design and interact with them in real space, unattached by headset, fixed cameras or screen. ReShape can be controlled by user orien-tation and gesture as an input, where the real-time feedback is provided by UAV spatial arrangement in space, augmented by computational simulation. Spatial data is transmitted between the UAV agents for the user to experience the digital model, creating a versatile and computationally efficient platform to edit and en-hance the design in real-space.

## Alexander Grasser

1.**[Pervasive Collaboration and Tangible Complexity in Realtime Architecture](https://www.researchgate.net/publication/344270210_Pervasive_Collaboration_and_Tangible_Complexity_in_Realtime_Architecture)**

**Grasser,A, Parger, A, Hirschberg,U.**

*Abstract*

This paper reports on an ongoing experiment in design collaboration: an open collaborative realtime environment that enables participatory design activities in spatially distributed teams. The project builds on online platforms and open source ways of sharing design ideas, but also on recent advances in shared augmented reality enabled by game engine technology. Furthermore it focuses on combinatorial design of collaborative objects: the models shared in this way are not just geometric forms, but informed systems of parts with a procedural or combinatorial logic, an assembly strategy. By pooling and aggregating such intelligent assembly systems in a shared online realtime design space we are trying to move towards pervasive collaboration in architecture. Authors taking part in the project are united in a shared persistent design space and can design collectively. They experience what we refer to as tangible complexity: a playful mode of aggregating and combining design ideas of different authors. We argue that this pervasive collaboration can lead to novel types of complexity: an architecture of socially augmented formations.

2.**[Reappraising Configuration and its Potential for Collaborative Objects](https://www.researchgate.net/publication/354474923_Reappraising_Configuration_and_its_Potential_for_Collaborative_Objects)**

**Grasser, A. Parger, A.**

*Abstract*

This year's conference theme`Towards a new configurable architecture`, provides a good starting point for reappraising and reapplying previous concepts of Configuration' in architectural design. The concept reappears often, but was particularly powerful whenever new computational tools and architectural concepts emerged and revealed strong synergies. In the 1960ties there was such a moment when configuration's pluralistic properties embraced architectural concepts of structuralism and early computing. Therefore this paper looks back at previous concepts of configuration to identify capacities that could inform current synergies of computational tools, such as open platforms, and architectural concepts of the second digital turn in architecture. The way we communicate, access, and exchange information recently accelerated towards realtime sharing of data, bits & pieces, and experiences. Open platforms that enable user-generated content and collective production of value are becoming more common in design. This paper discusses ways in which this collective content production can enable a computational and human-centric architecture, by reappraising previous concepts of configuration such as: open configurations, latent structures and variable infills.

3.**[Realtime Architecture Platform Collab Wood](https://www.researchgate.net/publication/356557159_Realtime_Architecture_Platform_Collab_Wood)**

**Grasser, A, Parger, A., Hirschberg, U.**

*Abstract*

This project proposes a realtime architecture platform. It's based on previous research on collaborative architecture (Grasser 2019) as well as research on combinatorial design (Sanchez 2016), digital architecture (Carpo 2013), and discrete mereologies (Koehler 2019). The platform was applied in a design studio at the Institute of Architecture and Media at Graz University of Technology with 20 Masters students. Due to restrictions of the global pandemic, we worked in a distributed mode of telepresent teaching. The implementation of this new working method further accelerated the focus on digital collaboration in architecture. Using the platform to collaborate in real time, the Collab Wood prototype was designed and realized.

4.**[Blockchain Architectures, the Potential of Web3 for Decentralized Participatory ArchitectureCollaborative obiects on the Blockchain](https://www.researchgate.net/publication/363504669_Blockchain_Architectures_the_Potential_of_Web3_for_Decentralized_Participatory_Architecture_-_Collaborative_objects_on_the_Blockchain)**

**Grasser, A, Parger, A**

*Abstract*

This paper explores the potential of blockchain technology and the Web3 for a decentralized participatory architecture. In this context, the polyvalent capacity of a block in a blockchain is at the center of this investigation. Blockchain innovations in cryptography and efficient block validation and creation systems have led to autonomous blocks that act as decentralized, transparent, and secure Web3 assets. Following our previous research on collaborative objects that enable real-time participatory design activities, a case study project H=N BLOCK+A is developed that implements blockchain principles at both the conceptual and infrastructural levels. At the conceptual level, architectural blocks are speculated and applied as autonomous and decentralized Web3 assets, i.e., a decentralized kit of parts/blocks/NFTs/applications that can form a crazy patchwork of heterogeneous compatible blocks. At the infrastructural level, an existing sustainable blockchain is facilitated to embed a decentralized design methodology that enables real-time participatory co-creation of a collective architectural form.

5.**[Decentralized Participation and Agency in Digital Art and Architecture, An Exploration ofPixel and Voxel-Based Case Studies](https://www.researchgate.net/publication/373998468_Decentralized_Participation_and_Agency_in_Digital_Art_and_Architecture_An_Exploration_of_Pixel_and_Voxel-Based_Case_Studies?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InByb2ZpbGUiLCJwYWdlIjoicHJvZmlsZSJ9fQ)**

**Grasser, A.**

## Immanuel Koh

1.**[Your Memory Palace in the Metaverse with AI](https://www.researchgate.net/publication/375530571_Your_Memory_Palace_in_the_Metaverse_with_AI)**

**Immanuel Koh,Ashley Chen**

*Abstract*

The metaverse is recognised as an immersive environment where individuals congregate as avatars to perform activities in imaginary places, similar to how they would in reality. Although promising, it has been unsuccessful in retaining novelty with current renditions of the metaverse looking unappealing and devoid of human touch, lacking in genius loci. The objective of this paper is to construct a framework for the metaverse that is built directly from the human experience to become deeply personalized and meaningful, providing users with a unique and immersive experience. This paper proposes a framework for the metaverse that leverages wearable technology and artificial intelligence (AI) to generate virtual spaces based on the conscious and subconscious experiences of individuals.

2.**[CAADRIA 2023: HUMAN-CENTRIC - Volume 1](https://www.researchgate.net/publication/371449483_CAADRIA_2023_HUMAN-CENTRIC_-_Volume_1)**

**Immanuel Koh,Dagmar Reinhardt,Mohammed Makki,Mona Khakhar**

3.**[CAADRIA 2023: HUMAN-CENTRIC - Volume 2](https://www.researchgate.net/publication/371449631_CAADRIA_2023_HUMAN-CENTRIC_-_Volume_2)**

**Immanuel Koh,Dagmar Reinhardt,Mohammed Makki,Mona Khakhar**

4.**[Palette2Interior Architecture: From Syntactic and Semantic Colour Palettes to Generative Interiors with Deep Learning](https://www.researchgate.net/publication/372019867_Palette2Interior_Architecture_From_Syntactic_and_Semantic_Colour_Palettes_to_Generative_Interiors_with_Deep_Learning)**

**Immanuel Koh**


>## More

**Immanuel Koh**    

https://www.researchgate.net/profile/Immanuel-Koh

**Alexander Grasser**

https://www.researchgate.net/profile/Alexander-Grasser-Parger




