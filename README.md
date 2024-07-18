# MPCKD
A multi-stage prediction comparison algorithm based on self-supervised learning is proposed for knowledge distillation. It designed three distinct knowledge distillation feature extraction modules: the staged response distillation mechanism, the staged relationship distillation mechanism, and the staged self-supervised distillation mechanism, and transferred sufficient composite knowledge from a strong teacher model to a lightweight student model via a multi-stage learning mechanism. The overall idea of the knowledge distillation compression framework is: 1) the staged response distillation mechanism is constructed, performing direct feature matching for individual samples using class prototypes, and distilling fundamental semantic features at the final output layer; 2) the staged relationship distillation mechanism is proposed to extract valid knowledge between samples, which could transfer the internal relationships captured by the teacher model to the student model, achieving knowledge distillation results; 3) the staged self-supervised distillation mechanism is designed to enable the student’s auxiliary classifier to learn self-supervised augmented distributions, extending the traditional knowledge distillation from the simulation of a single classification task to the imitation of transformed images. In this method, the teacher network incorporates rich structured knowledge through self-supervised prediction training on transformed images. Experimental results on different scale image classification datasets demonstrate that the proposed method is able to greatly reduce the number of model parameters while improving the model performance, and effectively improve the inference speed of the lightweight model in practical application scenarios.

 ![](MPCKD/img/mpckd_main.png)
