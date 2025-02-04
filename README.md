## Overview
This repository contains my completed coursework for Deep Representations and Learning at University College London. The coursework involves building a supervised learning model which clones the behavior of a robotic arm using a dataset of images and sequences of actions. To reduce the dimensionality of the image inputs, I then construct a series of Variational Autoencoders to encode the images into a latent space. Finally, I use the latent representations of the images as inputs into a downstream supervised learning model and evaluate its performance against the original supervised model. 

## Repository Structure
```
root/
├── README.md         # This file
├── robotic_behavioral_cloning.ipynb    # Jupyter notebook containing code and analysis
├── src/comp0188_cw2/ # Folder containing helper functions and source code to execute notebook
```

## Data Source

Download the data for the project from here: https://drive.usercontent.google.com/download?id=1tVSilmXhyQd8gxZAEhvKMnynw0qzRFSZ&authuser=0. More information on the dataset can be found at: https://github.com/clvrai/clvr_jaco_play_dataset?tab=readme-ov-file.

## Notes
- This repository showcases my approach to solving the coursework problems.
- Original coursework-related details (e.g., specific instructions and rubric) have been removed for professional presentation.
  
## License
This project is for educational purposes and should not be used for commercial purposes. Helper functions in comp0188_cw2/ were provided as part of the coursework and are not my original work.

---

For any questions or feedback, feel free to reach out or open an issue in the repository.
