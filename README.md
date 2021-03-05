# DCGANs
Deep Convolutional Generative Adversarial Network on Celebrity Faces Dataset 

# Dataset
CelebA

![Sampled Faces from the dataset](./fake_rgd/epoch_=_0.png)


# Results

## Generated Images Through Training

Epoch 1           |  Epoch 3
:-------------------------:|:-------------------------:
![Epoch 1](./fake_rgd/epoch_=_0.png)  |  ![Epoch 3](./fake_rgd/epoch_=_2.png)

Epoch  21           |  Epoch 62
:-------------------------:|:-------------------------:
![Epoch 21](./fake_rgd/epoch_=_20.png)  |  ![Epoch 62](./fake_rgd/epoch_=_61.png)

## Discrimnator and Generator losses

Generator           |  Discriminator
:-------------------------:|:-------------------------:
![loss of generator](./losses_figures/loss_of_generator.png)  |  ![loss of discriminator](./losses_figures/loss_of_discriminator.png)

## Dicriminator's mean prediction on real and on generated data

Real Images           |  Fake Images
:-------------------------:|:-------------------------:
![discrimantor's mean prediciton on real images](disc_mean_pred_on_real.png)  |  ![discrimantor's mean prediciton on fake images](./losses_figures/disc_mean_pred_on_fake.png)

