# Graph-Based Face Image Reconstruction Using GNNs


This project focuses on reconstructing face images using Graph Neural Networks (GNNs) with the Morph2 dataset. By constructing facial graphs through the dlib library, the project converts these graphs into tensors to generate embeddings with a GNN encoder. In addition to reconstructing images from the dataset, it also generates face images based on sketch inputs. The reconstructed images are created by decoding embeddings in conjunction with image data. Model accuracy is evaluated using Mean Squared Error (MSE) to compare original and reconstructed images.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone this repository and install the required packages. Ensure you have Python 3.7+ installed. You can install the necessary libraries using pip:

```bash
git clone https://github.com/yourusername/graph-based-face-reconstruction.git
cd graph-based-face-reconstruction
pip install -r requirements.txt
