# Deep Learning Architectures: A Learning Journey

A comprehensive collection of implementations and experiments with various deep learning architectures, from fundamental building blocks to state-of-the-art models. This repository serves as both a learning resource and a reference for representation learning and generative models.

## 📚 Repository Structure

```
├── 1_fundamentals/              # Core neural network architectures
├── 2_autoencoders/              # Representation learning models
├── 3_attention_mechanisms/      # Attention-based architectures
├── 4_advanced_architectures/    # Modern deep learning models
└── 5_multimodal/                # Cross-modal learning
```

## 🏗️ Implemented Architectures

### 1. Fundamental Architectures

#### Sequential Models
- [x] **RNN (Recurrent Neural Networks)** - Binary addition task
- [ ] LSTM (Long Short-Term Memory)
- [ ] GRU (Gated Recurrent Units)
- [ ] Bidirectional RNN

#### Feedforward Networks
- [ ] Multilayer Perceptron (MLP)
- [ ] Deep Neural Network (DNN)
- [ ] Batch Normalization

#### Convolutional Networks
- [ ] Basic CNN
- [ ] LeNet-5
- [ ] AlexNet
- [ ] VGGNet

#### Regularization Techniques
- [ ] Dropout
- [ ] Weight Decay
- [ ] Data Augmentation

### 2. Autoencoders & Representation Learning
- [x] **Vanilla Autoencoder** - Image compression with PyTorch
- [x] **Denoising Autoencoder** - Noise reduction with PyTorch
- [x] **Convolutional Autoencoder** - CNN-based with TensorFlow
- [x] **Variational Autoencoder (VAE)** - Generative model
- [ ] Adversarial Autoencoder (AAE)
- [ ] Vector Quantized VAE (VQ-VAE)
- [ ] Beta-VAE

### 3. Attention Mechanisms & Transformers
- [x] **Simple Attention Model** - Financial time series prediction
- [x] **Vision Transformer (ViT)** - Image classification with patches
- [ ] BERT (Bidirectional Encoder Representations)
- [ ] GPT (Generative Pre-trained Transformer)
- [ ] Multi-head Self-Attention
- [ ] Cross-Attention

### 4. Advanced Architectures
- [x] **MLP-Mixer** - All-MLP architecture for vision
- [ ] ConvNeXt
- [ ] ResNet (Residual Networks)
- [ ] EfficientNet
- [ ] DenseNet
- [ ] U-Net

### 5. Multimodal Learning
- [x] **CLIP** - Contrastive Language-Image Pre-training
- [ ] DALL-E
- [ ] Flamingo
- [ ] ImageBind

### 6. Generative Models
- [ ] GAN (Generative Adversarial Network)
- [ ] StyleGAN
- [ ] Diffusion Models
- [ ] Stable Diffusion
- [ ] Flow-based Models

### 7. Graph Neural Networks
- [ ] GCN (Graph Convolutional Networks)
- [ ] GraphSAGE
- [ ] GAT (Graph Attention Networks)

### 8. Reinforcement Learning
- [ ] DQN (Deep Q-Network)
- [ ] Policy Gradient Methods
- [ ] Actor-Critic
- [ ] PPO (Proximal Policy Optimization)

## 🎯 Learning Path

The repository is organized to follow a logical learning progression:

1. **Start with Fundamentals** - Understand basic recurrent architectures
2. **Explore Autoencoders** - Learn representation learning and compression
3. **Master Attention** - Dive into modern attention mechanisms and transformers
4. **Advanced Architectures** - Experiment with cutting-edge models
5. **Multimodal Learning** - Combine different data modalities

## 🛠️ Technologies Used

- **PyTorch** - Primary deep learning framework
- **TensorFlow** - Secondary framework for specific implementations
- **NumPy** - Numerical computing
- **Matplotlib** - Visualization
- **Jupyter Notebooks** - Interactive development

## 📖 How to Use

Each directory contains Jupyter notebooks with:
- Theoretical background and architecture explanations
- Step-by-step implementation from scratch
- Training procedures and hyperparameters
- Visualization of results
- Code comments and documentation

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Ekliipce/Representation-and-Generative-Learning.git

# Navigate to a specific architecture
cd Representation-and-Generative-Learning/2_autoencoders

# Open the notebook
jupyter notebook AutoEncoder_for_Image_Compression_(with_pytorch).ipynb
```

## 📝 Notebooks Overview

### Fundamentals
- `Reimplémentation_RNN.ipynb` - RNN implementation for binary string addition

### Autoencoders
- `AutoEncoder_for_Image_Compression_(with_pytorch).ipynb` - Compression using Conv layers
- `AutoEncoder_Denoiser_(with_pytorch).ipynb` - Noise removal from images
- `CNN_Autoencoder_(tensorflow).ipynb` - TensorFlow implementation
- `Variationnal_Auto_Encoder.ipynb` - VAE for generative modeling

### Attention & Transformers
- `Simple_attention_model_to_predict_a_financial_time_series.ipynb` - Attention basics
- `Transformer_Deepcourse.ipynb` - Vision Transformer (ViT) implementation

### Advanced
- `MLP_Mixer_Deepcourse.ipynb` - All-MLP architecture for vision tasks

### Multimodal
- `TP_CLIP.ipynb` - CLIP model for fashion dataset

## 🎓 Learning Resources

### 📚 Books

#### Foundational Deep Learning
- **Deep Learning** by Ian Goodfellow, Yoshua Bengio, and Aaron Courville
  - [Online version](https://www.deeplearningbook.org/)
  - Comprehensive theoretical foundation

- **Deep Learning with Python** by François Chollet (Keras creator)
  - Practical approach with Keras and TensorFlow
  - Second edition covers modern deep learning practices

- **Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow** by Aurélien Géron
  - Practical implementation guide
  - Covers end-to-end ML projects

#### Specialized Topics

- **Hands-On Large Language Models** by Jay Alammar & Maarten Grootendorst
  - Modern LLM architectures and fine-tuning
  - Practical implementations with transformers

- **Generative Deep Learning** by David Foster
  - VAEs, GANs, and Diffusion Models
  - Creative AI applications
  - Second edition includes latest generative techniques

- **Natural Language Processing with Transformers** by Lewis Tunstall, Leandro von Werra & Thomas Wolf
  - Hugging Face Transformers library
  - BERT, GPT, T5, and modern NLP architectures

#### Computer Vision
- **Deep Learning for Computer Vision** by Rajalingappaa Shanmugamani
  - CNN architectures and applications
  - Object detection and segmentation

- **Programming PyTorch for Deep Learning** by Ian Pointer
  - PyTorch-focused implementations
  - Transfer learning and deployment

### 🌐 Online Resources

#### Interactive Courses & Books
- [Dive into Deep Learning](https://d2l.ai/) - Interactive book with code examples
- [FastAI Course](https://course.fast.ai/) - Practical deep learning for coders
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by Michael Nielsen
- [The Little Book of Deep Learning](https://fleuret.org/francois/lbdl.html) by François Fleuret

#### Research & Implementation
- [Papers with Code](https://paperswithcode.com/) - Latest papers with implementations
- [Distill.pub](https://distill.pub/) - Visual and interactive explanations
- [Andrej Karpathy's Blog](http://karpathy.github.io/) - Deep insights on neural networks
- [Lil'Log](https://lilianweng.github.io/) by Lilian Weng - Architecture deep dives

#### Architecture-Specific Resources
- [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) by Jay Alammar
- [The Annotated Transformer](http://nlp.seas.harvard.edu/annotated-transformer/)
- [Hugging Face Course](https://huggingface.co/course) - Transformers and NLP
- [PyTorch Tutorials](https://pytorch.org/tutorials/) - Official tutorials
- [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) - Official guides

#### Video Courses
- [Stanford CS231n](http://cs231n.stanford.edu/) - Convolutional Neural Networks for Visual Recognition
- [Stanford CS224n](http://web.stanford.edu/class/cs224n/) - Natural Language Processing with Deep Learning
- [MIT 6.S191](http://introtodeeplearning.com/) - Introduction to Deep Learning
- [DeepLearning.AI Specialization](https://www.deeplearning.ai/) by Andrew Ng

### 📄 Research Papers Collections
- [Awesome Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers)
- [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
- [Awesome NLP](https://github.com/keon/awesome-nlp)

## 🤝 Contributing

This is a personal learning repository, but suggestions and improvements are welcome! Feel free to:
- Open issues for bugs or unclear implementations
- Suggest new architectures to implement
- Share learning resources

## 📄 License

This project is open source and available for educational purposes.

## 🔗 References

Key papers implemented in this repository:
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Transformer
- [An Image is Worth 16x16 Words](https://arxiv.org/abs/2010.11929) - ViT
- [MLP-Mixer: An all-MLP Architecture for Vision](https://arxiv.org/abs/2105.01601)
- [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020) - CLIP
- [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114) - VAE

---

⭐ **Progress**: 8/50+ architectures implemented and counting!
