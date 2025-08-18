# Superior_colliculus_CNN
A project for predicting turn direction from superior colliculus neural activity using a CNN
- The superior colliculus (SC) is a midbrain region that encodes turn direction. Can we predict turn direction from SC spiking activity using a convolutional neural network?
- Goal: By treating matrices of SC spiking data (neurons x time) as 'images' with labels of right or left turns, can we build a CNN to classify the images by turn direction? What might the model internals (filters) reveal about which neurons are predictive or non-predictive of turn direction?
- Data: Bilateral recording from mouse SC during a Y-maze navigation task (75 total neurons).
