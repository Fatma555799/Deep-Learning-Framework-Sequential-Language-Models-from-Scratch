# Deep Learning Framework: Sequential Language Models from Scratch

A comprehensive  repository implementing **Sequential Language Models** from the ground up using PyTorch.

## 🎯 Project Goal

To deeply understand how modern language models work by building them **step by step** from the simplest statistical models to more advanced neural architectures — all without relying on high-level libraries.

## 🛠️ Tools & Technologies

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google%20Colab&logoColor=white)

</div>

## 📌 Project Structure

```bash
Deep-Learning-Framework-Sequential-Language-Models-from-Scratch/
├── micrograde_from_scratch.ipynb          # Micrograd implementation + exercises
├── trigrad.py / mlp2.py / mlp_3.py        # MLP experiments & backpropagation
├── makemore1.py                           # Basic Bigram model (counting + NN)
├── build_makemore_mlp.py                  # MLP-based character-level language model
├── build_makemore_batchnorm.py            # Adding Batch Normalization + improvements
├── build_makemore_backprop_ninja.py       # Manual backpropagation mastery
├── building_a_wavenet.py                  # WaveNet-style architecture
├── gpt_bigram.py                          # GPT-style Bigram model
├── gpt_v2.py                              # More advanced GPT implementation
└── README.md

🚀 Progression

Stage,File,description 
1,micrograde_from_scratch.ipynb,Building a neural network engine (Autograd) from scratch
2,makemore1.py,Bigram model using counting and simple Neural Network
3,build_makemore_mlp.py + mlp*.py,Multi-Layer Perceptron for character prediction
4,build_makemore_batchnorm.py,"Batch Normalization, better optimization, and training tricks"
5,build_makemore_backprop_ninja.py,Deep understanding of backpropagation
6,building_a_wavenet.py,WaveNet architecture (dilated convolutions)
7,gpt_bigram.py & gpt_v2.py,Transformer-style GPT models

✨ Key Concepts Covered

Character-level tokenization
Embedding layers & neural networks (MLP → WaveNet → GPT)
Backpropagation & gradient computation
Batch Normalization and training techniques
Text generation
Model evaluation and progressive improvement

🛠️ How to Run

Clone the repository:
Bash
git clone https://github.com/Fatma555799/Deep-Learning-Framework-Sequential-Language-Models-from-Scratch.git
cd Deep-Learning-Framework-Sequential-Language-Models-from-Scratch
Install dependencies:
Bash
pip install torch torchvision torchaudio matplotlib tqdm
Run any script:
Bash
python makemore1.py
# or
python gpt_v2.py

📈 Results
Each model builds upon the previous one, showing clear improvement in loss and generation quality — from basic Bigram to advanced GPT-style architectures.
🔮 Future Work (TODO)

 Full Transformer (nanoGPT style)
 Training on large Arabic dataset
 Web demo (Streamlit/Gradio)
 Model optimization and inference

📚 References & Inspiration

Andrej Karpathy - Neural Networks: Zero to Hero

Built with ❤️ by [Fatma Mansour]
Learning Deep Learning by building it from scratch.
