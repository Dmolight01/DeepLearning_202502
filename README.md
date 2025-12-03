# DeepLearning_202502
Repositorio para el proyecto de la materia electiva Deep Learning en la Universidad de Antioquia. Este proyecto implementa un sistema completo de Deep Learning para clasificación de imágenes, integrando técnicas modernas de preprocesamiento, arquitecturas basadas en CNN, optimización, regularización y evaluación. El objetivo principal es demostrar la aplicación práctica de modelos convolucionales en un entorno reproducible, estructurado y documentado según buenas prácticas.

Inclusión completa de materiales
El repositorio incluye:

✔️ Notebooks con la solución completa del proyecto

✔️ Informe de la primera entrega

✔️ Presentaciones y documentación adicional relevante

✔️ Scripts auxiliares y código fuente necesario para su ejecución

Todo está debidamente organizado para facilitar la revisión.

Instalación del Proyecto

Crear entorno virtual (opcional) python -m venv venv source venv/bin/activate # Linux/macOS venv\Scripts\activate # Windows

Instalar dependencias pip install -r requirements.txt

Uso del Proyecto Preprocesamiento de datos python src/dataset.py

Entrenamiento del modelo python src/train.py --epochs 50 --batch-size 32 --lr 0.001

Evaluación python src/evaluate.py --model models/best_model.pth

Resultados

Los resultados del proyecto incluyen:

Curvas de entrenamiento (loss y accuracy)

Matriz de confusión

Consideraciones Técnicas

Arquitectura basada en CNN con BatchNorm, Dropout y capas densas.

Data Augmentation para mejorar generalización.

Optimizador: Adam

Función de pérdida: CrossEntropyLoss

Entrenamiento reproducible mediante semillas controladas.

Código modular y escalable para experimentos adicionales.

Equipo
José Alfredo Martínez Valdés
Dorian Alexander Jaramillo Rivas
Wilmer Mario Leiva Esteban

Reporte de métricas (accuracy, F1, recall, precision)
