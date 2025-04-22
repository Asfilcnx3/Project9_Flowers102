# Project9_Flowers102

## Español
> En este proyecto utilicé una red neuronal simple con 102 salidas (categorías) para una clasificación multinomial pero con "Transfer Learning" del modelo "IMAGENET1K_V2" que fue preentrenado para clasificación de imagenes. 

## English
> In this project i used a Simple NN with 102 output layers (categories) for a multinomial classification but with "Transfer Learning" of the "IMAGENET1K_V2" model that was pretrained for image classification.

## Descripción / Description
> - Este es un proyecto de visión por computadora con torch.cuda para acelerar manualmente el entrenamiento. Este proyecto es para hacer la comparación entre "congelar" las capas de atención y seguir entrenandolas en una clasificación de 102 tipos diferentes de imagenes. 
> 
> - Se utilizó PyTorch como herramienta principal y el set de datos "Flowers102" que viene en `torchvision.datasets`.
> 
> - Se Trabajó con muchisima Data Augmentation. Con 5 capas y la normalización.
> 
> - Se usó EarlyStopping a 7 épocas de paciencia.
> 
> - 50 épocas de entrenamiento totales para ambos modelos.
> 
> - BatchSize de 32 imagenes.
> 
> - Trabajamos con set de Validación, Entrenamiento y Prueba.

> -------------------

> - This is a computer vision project using torch.cuda to manually accelerate the training loop. This project is to compare the accuracy between "Fine Tuning" and "Feature Extraction" in a 102 different output categories.
> 
> - Using PyTorch as main tool and the "Flowers102" dataset that you can find on `torchvision.datasets`.
> 
> - Worked with 5 different layers of Data Augmentation and the normalize layer.
> 
> - EarlyStopping was used with 7 patience epochs.
> 
> - 50 total epochs for both models.
>
> - BatchSize = 32
>
> - Worked with train, test and valid split.

## Tecnologías usadas / Used Technologies
- Python (main)
- PyTorch
- Google Colab / Jupyter NoteBook
- Matplotlib, Seaborn
- Sklearn
- CUDA
- IMAGENET1K_V2

## Final Results / Resultados Finales
Comparación de ambos modelos

        Fine Tuning:           Loss: 0.490     Accuracy: 87.79%
    ============================================================
        Feature Extractor:     Loss: 0.675     Accuracy: 85.97%


