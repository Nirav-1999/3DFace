# 3DFace

The repository implements a conditional GAN with a Markovian discriminator and a U-Net based generator to generate 3d point clouds
from 2d face images. The generator was trained using a weighted L1 loss and adversarial loss on the AFLW2000-3D dataset. The point
clouds were generated using 3DDFA on the dataset.
