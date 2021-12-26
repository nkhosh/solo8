# CPSC 533V Term Project: Deep Reinforcement Learning for the Open Dynamic Robot Initiative Solo 8 Robot

Yuni Fuchioka, Dylan Green, Niloofar Khoshsiyar

University of British Columbia

CPSC 533V 2021W Course Project


# Supplementary Materials

## 2.6 Experiment 2: Observation Ablation

Reference Motion Used for "Walking Back and Forth" Task

https://user-images.githubusercontent.com/5961296/146656060-64fa0132-ea88-4992-b02a-13715e3bcaad.mp4

## 3.1 Motion Diversity
Standing in place with an initial jump

https://user-images.githubusercontent.com/5961296/146664181-09c668a2-41b3-4166-a59c-e231e94f7a45.mp4

## 3.2 Observation Ablation
Full Observation

https://user-images.githubusercontent.com/5961296/146656191-aea90a4f-641e-42a7-b709-12854dfda926.mp4



Phase and Joint

https://user-images.githubusercontent.com/5961296/146656193-29f485a1-c5f5-4927-9de5-b7081f5a4b0e.mp4



Phase and IMU

https://user-images.githubusercontent.com/5961296/146656195-4251fc0b-8095-4d1f-a58e-3d759bd9e1c6.mp4



Phase Only

https://user-images.githubusercontent.com/5961296/146656198-577b9592-d051-4760-937f-d68818b83f28.mp4

## 4.1 Motion Diversity Discussion

Failed attempt at walking motion

https://user-images.githubusercontent.com/5961296/146664229-25dea2c9-d8f7-403b-957a-c00bf75cc088.mp4


## 4.3.2 Tuning of Rewards vs Termination Conditions

Unsuccessful Policy with Poorly Tuned Rewards

https://user-images.githubusercontent.com/5961296/146656567-5630b5df-3bfc-4a39-ad8e-de1de2ff8b3f.mp4


Successful Policy Through Tuning Position Rewards

https://user-images.githubusercontent.com/5961296/146656568-69c9613f-edd5-4267-b048-bf197d41178c.mp4



Improved Policy with Position Error Termination

https://user-images.githubusercontent.com/5961296/146656571-0787bf44-3894-4109-b8f2-2afe07f32180.mp4



## 4.3.3 Incorrect Use of Regularization Rewards

"Step in Place" Motion with Torque Maximization Regularization (Bug)

https://user-images.githubusercontent.com/5961296/146656575-6e96e557-17dd-4d58-8f59-418fee5a6ce0.mp4


"Walk Back and Forth" Motion with Torque Maximization Regularization (Bug)

https://user-images.githubusercontent.com/5961296/146656578-f30e186d-b817-4b03-8738-24c368836396.mp4



"Walk Back and Forth" Motion with Torque Minimization Regularization (Bug Fixed)

https://user-images.githubusercontent.com/5961296/146656582-2c0ed51c-4cbf-4ea2-9c36-49a311dfe5ec.mp4


## 4.3.4 Sim-to-Real Considerations for Motion Design
Phase Only Walking with No Angular Velocity Termination

https://user-images.githubusercontent.com/5961296/146656620-e67de863-e65f-4e4d-954b-ce302ce8b851.mp4



Phase Only Walking with Angular Velocity Termination

https://user-images.githubusercontent.com/5961296/146656656-1938c0e3-108d-4336-8857-b0623c8acf28.mp4



Reference Motion Used for Sine "Walk Back and Forth" Motion

https://user-images.githubusercontent.com/5961296/146656661-1f14c31a-d6bb-48db-b46f-405eb6c94741.mp4



Result of Training Sine "Walk Back and Forth" Motion

https://user-images.githubusercontent.com/5961296/146656662-41a22cf8-c79b-47eb-8ebf-e290f51a617d.mp4



Reference Motion Used for Cosine "Walk Back and Forth" Motion

https://user-images.githubusercontent.com/5961296/146656665-9c66ce24-2216-4eae-a411-afc8881ae65a.mp4



Result of Training Cosine "Walk Back and Forth" Motion

https://user-images.githubusercontent.com/5961296/146656666-cca9888b-14dc-4e13-8c41-09adfcded4cc.mp4

## 4.3.5 Reference State Initialization

Reference Motion Used for Flipping Motion

https://user-images.githubusercontent.com/5961296/146657147-226cbeda-7597-442a-9cc5-5aa9cc71a801.mp4


Result of Training Flipping Motion using Naive "Pseudo-RSI" (Failure)

https://user-images.githubusercontent.com/5961296/146657150-b6f8cab3-da7e-4170-be60-585842179086.mp4



## 4.3.6 Physical Limitations vs. RL Design Limitations, Preliminary Turning Experiments
Reference Motion Used for "Turn in Place" Motion

https://user-images.githubusercontent.com/5961296/147398323-6ae7730c-362a-429a-90b8-8df6217690a9.mp4


Phase Only "Turn in Place" Motion (Failure)

https://user-images.githubusercontent.com/5961296/147398337-c89a42c0-2e34-4111-99b9-13036b2919f8.mp4



Phase Only "Turn in Place" Motion with No Position and Angular Velocity Error Termination (Failure)

https://user-images.githubusercontent.com/5961296/147398339-6dd799b1-6df8-4d91-a63b-0ec1f11315fd.mp4



Reference Motion used for "Circular Walk" Motion

https://user-images.githubusercontent.com/5961296/147398341-ab8861d0-33ac-4923-b5a8-d36324c2f21f.mp4



Phase Only "Circular Walk" Motion (Failure)

https://user-images.githubusercontent.com/5961296/147398349-1c528053-7284-4216-8d64-46cd124b4a2a.mp4



