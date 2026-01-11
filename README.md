DeepAdvance

This project explores how to turn pictures of one animal into another (like a cat into a dog) using AI. We compared three different methods: VAEs, CycleGAN, and Diffusion Models to see which one works best on the AFHQ dataset.
Dependencies

This project was built using Python. The main libraries used are:

- NumPy: For data handling.

- PyTorch & Torchvision: For building and training the AI models.

- Matplotlib: To plot and visualize the images.

- Transformers: For utilizing the CLIP encoder.

Installation Guide

Follow these steps to set up the project on your machine.
1. Get the code

Open your terminal (or Git Bash) and clone the repository:
Bash

```bash
git clone https://github.com/robertbejan/deepavance.git
cd deepavance
```

2. Create the Virtual Environment

On Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

On Mac/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install Dependencies

```bash
pip install numpy torch torchvision matplotlib notebook transformers
```

4. How to Run

The project uses Jupyter Notebooks. To run the code:

Start the notebook server:

```bash
jupyter notebook
```

A browser window will open. Click on one of the project files (e.g., miniproject_cycleGAN.ipynb or miniproject_diffusion.ipynb).

Run the cells in order (from top to bottom) to reproduce the experiments.
