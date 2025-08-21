# Comparison-of-AlexNet-VGG-and-ResNet-on-Fashion-Dataset-MNIST
🧥 Fashion-MNIST Classification using VGG16, ResNet50, and AlexNet

This project compares the performance of three deep learning models — VGG16, ResNet50, and AlexNet — on the Fashion-MNIST dataset using only 2000 training and testing images.
The experiment was conducted in Google Colab with TensorFlow/Keras.

📂 Dataset: Fashion-MNIST

Source: Fashion-MNIST

Contains 70,000 grayscale images of fashion items (10 classes).

We used only 2000 images for both training and testing to make training faster.

🚀 Models Trained

VGG16 (pre-trained on ImageNet, with frozen layers + dense classifier).

ResNet50 (transfer learning, pre-trained on ImageNet).

AlexNet-like CNN (custom implementation since AlexNet is not in Keras).

📊 Experiment Setup

Input images resized to 224×224 and converted to 3 channels.

Optimizer: Adam

Loss: SparseCategoricalCrossentropy

Epochs: 5

Batch size: 64

Metrics: Accuracy
📈 Results (Example)
Model	Accuracy (2000 test images)	Training Time (5 epochs)
VGG16	~0.82	~45s
ResNet50	~0.85	~60s
AlexNet	~0.78	~70s

(Numbers will vary depending on runtime/Colab GPU availability.)

🛠️ How to Run

Open in Google Colab.

Copy the code above into a notebook cell.

Run all cells.

Compare results via graphs + accuracy table.
