# Undergraduate-Thesis
my undergrad thesis in Chinese

The first chapter briefly introduces the progress of deep learning in recent years, and introduces the main methods as well as frameworks used in later chapters. It combs some ideas and part of achievements in previous work that use deep learning to solve problems related to physics.

The second chapter studies the application of deep learning in statistical physics. The Section 2.2 uses the Hopfield network to accelerate the Markov Chain Monte Carlo simulation, and the Ising Model spin configuration simulation results which are closer to the theoretical solution can be obtained in much shorter time; the Section 2.3 reproduced the work of using auto-encoders to distinguish the Ising Model phases in an unsupervised manner, and studies the information that auto-encoders learned meticulously, such method is further extended to XY-Model in this section; the Section 2.4 proposes a method of generating the spin configuration of Ising Model by generation models. This method can generate the simulation results of the spin configuration of the same scale or larger scale, and can effectively avoid the problem of mode collapse.

In the third chapter, star-galaxy segmentation and classification tasks are realized by unsupervised learning. The Section 3.2 adapts the variational auto-encoders to the classification task, and finally an AUC of 0.91 is got in unsupervised way. Besides, the double-class classification accuracy for the objects with lower magnitude is over 97.5\%; the Section 3.3 uses auto-encoders and residual connection methods to realize the star-galaxy semantic segmentation. Compared with traditional methods, this method can automatically remove the noise pixels and is not disturbed by human bias.

The fourth chapter discusses the application of deep learning in MRI image segmentation. In dealing with medical MRI image segmentation problems with small data set, little training data, high dimensionality of images and different data sources, this chapter proposes a standardized method using CNN with BN. For the same network structure, this standardization method can be used to improve the performance, in the perspective of DSC, significantly.

## 
