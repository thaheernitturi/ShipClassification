-> Identifying different types of vessels from bird-view images captured by UAVs (Unmanned Aerial Vehicles) in the maritime industry presents a challenge,primarily due to the substantial cost and time required for acquiring and
 annotating extensive datasets.
 ->To address these issues, The Viewpoint Adaptation Ensemble Contrastive Learning (VAECL) framework is introduced.
 ->Initially, we confront the scarcity of annotated data by developing an enhanced deep generative model (DGM) within VAECL. 
 ->This enables the model to learn from a limited set of vessel images and generate additional ones to augment the training process. 
 ->In addressing the challenge of accurate vessel identification, we leverage transfer learning through a pre-trained Inception V3 network, specifically adapting the model for processing bird-view images captured by UAVs.
 ->Introducing a contrastive learning paradigm, we enhance the model's ability to discern between different vessel types using a novel loss function, thereby improving feature representation. 
 ->Furthermore, we incorporate an ensemble learning algorithm to fine-tune vessel type recognition, addressing potential challenges related to model variability and uncertainty. 
 ->This approach aims to offer a robust solution for UAV-based maritime vessel type identification, mitigating the difficulties associated with limited annotated data and the
 labor-intensive nature of image annotation tasks
