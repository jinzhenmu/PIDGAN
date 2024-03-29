# PIDGAN
Titile: An Automatic Control Perspective on Parameterizing GAN. 

Code will be available when papaer is accepted.

Abstract:  Generative adversarial networks (GANs) are effective in capturing high dimensional distribution but are notoriously tricky to optimize in the training process, which may result in mode collapse and instability. Current approaches deal with these issues in the parameter space for the purpose of regularization that undermines the convergence of GANs. Understanding and parameterizing GANs’ issues in the function space remain a challenge. This paper presents a conceptually new perspective from control theory to directly model the dynamics of GANs in the function space, demonstrating that these problems can be parameterized in a control formulation. First, we use linear control theory to understand GANs, specific to discriminator, and adopt a proportional-integral-derivative (PID) controller to improve its stability. GANs can be controlled to adaptively generate images by an overshoot rate that is only related to the parameters of the PID controller. Second, we derive a new PIDGAN with a theoretical guarantee of stability. Third, to exploit the nonlinear characteristics of GANs, we use nonlinear control theory to further analyze GANs and apply feedback linearization control to enhance the performance of PIDGAN.

![image](https://user-images.githubusercontent.com/48661603/135579753-0bddf594-3249-48d2-aebe-fe6f75e2df4e.png)
![image](https://user-images.githubusercontent.com/48661603/135579788-f28a58d6-7c66-4e76-8632-92bea00286cf.png)
