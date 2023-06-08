# Deep Quadric Learning - A tale in 4 episodes

What is quadric learning?
If digital technological evolution taught us one thing then it's this: Moore's 1st law will not always be on our side, his 2nd law never was.

The current hype concerning Large Language Models (LLM), the huge amount of data and parameters to build and train them clearly show that the trend of ever bigger data and ever bigger models can't be sustained and clearly negatively impacts

available AI compute power
AI costs
the democratization of access to AI technology
the AI carbon foot-print & sustainability of deep learning models
Everything that contributes positively in a meaningful way in order to improve the situation is absolutely crucial.

AI needs a paradigm shift because it is an illusion that much more progress can be achieved just by simply inflating model size and data. The JEPA approach of Yann LeCun seems to be a very promising next step but real world applicability is not imminent to say the least.

In the meantime, reducing the number of parameters is always a good idea.

This project of Deep Quadric Learning wants to be a small and humble contribution to the above mentioned dilemma by introducing quadric decision hypersurfaces, second order separability and enable the study of its impact on model size, parameters and interconnectivity of deep learning models. The idea for this project is based on my research thesis back in the day:

https://www.researchgate.net/publication/221582251_Using_Quadratic_Perceptrons_to_Reduce_Interconnection_Density_in_Multilayer_Neural_Networks

In one of the later episodes you'll find references to past and current research in this field including my own.

While attempting to directly reduce net model size itself, quadric learning at the same time still allows for various subsequent methods like hyper parameter optimization, model distillation, sparse activation, evolutionary architecture search etc. etc.

In 4 episodes this project will try to introduce the concept of quadric learning from the motivation (1) the single quadric neuron (2) to quadric layers (3) and lastly hybrid and purely quadric models (4).

The proof of concept implementation in PyTorch does in no way affect the applicability of Deep Quadric Learning to other frameworks like Tensor Flow etc.
