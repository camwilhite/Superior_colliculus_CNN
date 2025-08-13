CNN project for predicting turn direction from superior colliculus neural activity

- The superior colliculus (SC) is a midbrain region that encodes turn direction. Can we predict turn direction from SC spiking activity using a CNN?
- Data: Bilateral recording from mouse SC during a Y-maze navigation task (75 total neurons). Treat matrices of SC spiking data (neurons x time) as 'images' with labels of right or left turns
- Goal: Build CNNs to classify the images as right or left turns. Compare pure CNN and Hybrid CNN-Fully Connected models
