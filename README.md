# Universal Adversarial Perturbations on Visual Odometry Systems

In this work we are trying to take on the mission of improving an universal adversarial attack on Visual Odometry (VO) system. We use Projected Gradient Descent (PGD) as a baseline algorithm. We suggest a algorithm that uses momentum, Nestrov adaptive gradient step update and an adaptive method to replace the sign used in PGD and other algorithms. We also add rotation and flow losses that are used in tartanVO and other VO systems to measure the success of the VO in predicting the trajectory as part of our training. We also incorporated data augmentation to test and improve the model universality, which in the end did not work as expected. We were able to improve the out-ofsample results in comparison to the baseline algorithm and thus we are able to tell that our improvements to the algorithm can present better universality, i.e., creating perturbations that might have the ability to attack models in different environments and settings.

Read [report](report.pdf) for full detailes on goal, implementation and results.

![Augmentations](https://github.com/TalIfargan/universal_adversarial_perturbations_on_visual_odometry_systems/assets/65530510/f02d5f22-2bd1-496f-828f-b38a62f098af)
