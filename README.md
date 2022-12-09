# APCSC: Autonomous Point Cloud Scene Construction for Natural Disasters

## Introduction
APCSC is a project that uses state-of-the-art neural networks to create 3d models of natural disasters or predict forest fires. The project uses a transformer neural network to receive instructions from the user and control the drone, and a diffusion neural network to take images from the drone and construct the 3d model.

## How It Works
The transformer neural network is trained on a large dataset of instructions to understand and process user input. Once the user gives instructions, the neural network processes them and sends the appropriate commands to the drone.

The diffusion neural network uses the images taken by the drone to create a 3d model of the area. It processes the images and extracts important features, such as the location and shape of objects, to create a detailed and accurate 3d model.

## Limitations
APCSC is still in the development phase and has some limitations. The 3d models may not be perfect and may require further refinement. The predictions of forest fires may not be 100% accurate.

## License
APCSC is released under the MIT License.

## Acknowledgements
We would like to thank Google for providing access to their cloud computing resources, which were used to train the model.

## Citations
```
@inproceedings{Saharia2022PhotorealisticTD,
    title   = {Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding},
    author  = {Chitwan Saharia and William Chan and Saurabh Saxena and Lala Li and Jay Whang and Emily L. Denton and Seyed Kamyar Seyed Ghasemipour and Burcu Karagol Ayan and Seyedeh Sara Mahdavi and Raphael Gontijo Lopes and Tim Salimans and Jonathan Ho and David Fleet and Mohammad Norouzi},
    year    = {2022}
}
```
