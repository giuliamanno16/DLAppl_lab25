# DLAppl_lab25
Deep Learning Applications – Lab Collection
Questa repository contiene i notebook dei 4 laboratori del corso Deep Learning Applications (DLAppl). Ogni laboratorio esplora un tema diverso e avanzato del Deep Learning applicato.
| Lab                         | Titolo                                                   | Descrizione                                                                                                 |
| --------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Lab1-CNNs.ipynb**         | *Multilayer Perceptron, CNN e ResNet su MNIST/CIFAR10*           | Implementazione MLP e CNN, monitoraggio con TensorBoard, knowledge distillation con ResNet18 come teacher.  |
| **DLA-Lab2-DRL.ipynb**      | *Deep Reinforcement Learning*                            | Allenamento con REINFORCE con e senza baseline (anche Value Baseline), analisi delle prestazioni. |
| **Lab3-Transformers.ipynb** | *Sentiment Classification & Fine-tuning BERT*            | Classificazione binaria con SVM e fine-tuning di DistilBERT, uso di LoRA (PEFT), confronto prestazionale.   |
| **Lab4\_OOD\_2025.ipynb**   | *Out-of-Distribution Detection & Adversarial Robustness* | OOD detection con MSP e Autoencoder, attacchi FGSM mirati e non, robustezza e metriche ROC/PR.              |


# Esecuzione dei Notebook

**Su Google Colab**
Puoi aprire ogni notebook direttamente su Colab cliccando su: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_del_file_su_Colab)

**Localmente (conda o virtualenv)**

**Clona la repository:**

git clone https://github.com/giuliamanno16/DLAppl_lab25.git

cd DLAppl_lab25

**Crea un ambiente virtuale e installa le dipendenze:**

python3 -m venv venv

source venv/bin/activate  #oppure venv\Scripts\activate su Windows

pip install -r requirements.txt

**Esegui i notebook:**

jupyter notebook

# Requisiti

Tutti i notebook sono compatibili con Python ≥ 3.8. I pacchetti richiesti includono:

torch, torchvision

transformers, datasets

sklearn, matplotlib, seaborn

gym, numpy, tensorboard

Consulta requirements.txt per la lista completa.

# Autore

Giulia Manno – Deep Learning Applications Lab, A.A. 2024/2025
