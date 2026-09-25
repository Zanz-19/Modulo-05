# Módulo 05

Repositorio con los notebooks resueltos del Módulo 05 del programa **Talento Altamente Especializado – Inteligencia Artificial** (COCYTEN-Nayarit), organizados por instructor.

## Instructores

| Instructor | Tema del bloque |
| --- | --- |
| Antonio Ortiz (Cinvestav) | Modelos de difusión — ODEs/SDEs y flow/score matching |
| Germán | Autoencoders (AE, DAE, VAE, MAE) y transfer learning |
| Mario Iván López Valdovinos | Detección de objetos y segmentación de instancias con YOLO/COCO |
| Martín Pérez (TAE-IA) | Embeddings, seq2seq y arquitecturas transformer |

---

<details>
<summary><strong>Antonio</strong> — Modelos de difusión</summary>

| Archivo | Descripción |
| --- | --- |
| `lab_one_JRSA.ipynb` | Lab One: introducción práctica a la simulación de ODEs y SDEs (ecuaciones diferenciales ordinarias y estocásticas). |
| `lab_two_JRSA.ipynb` | Lab Two: recorrido práctico por *flow matching* y *score matching*. |

</details>

<details>
<summary><strong>German</strong> — Autoencoders y transfer learning</summary>

| Archivo | Descripción |
| --- | --- |
| `M5.1 Transfer Learning_JRSA.ipynb` | Transfer learning con ResNet-18: comparación entre sondeo lineal, afinación parcial (`layer4`) y afinación completa. |
| `M5.2 Autoencoder I_JRSA.ipynb` | Construcción de los bloques base (`DownBlock`/`UpBlock`) para autoencoders 1D, 2D y 3D. |
| `M5.2 Autoencoder II_JRSA.ipynb` | Entrenamiento de los autoencoders 1D/2D/3D sobre datos sintéticos (20 épocas cada uno). |
| `M5.3 DAE_JRSA.ipynb` | Denoising Autoencoder sobre MNIST: reconstrucción de dígitos limpios a partir de versiones con ruido gaussiano. |
| `M5.4 VAE_JRSA.ipynb` | Variational Autoencoder sobre MNIST: derivación paso a paso del término KL y entrenamiento con la pérdida VAE completa. |
| `M5.5 MAE_JRSA.ipynb` | Masked Autoencoder preentrenado sobre Cats vs Dogs, enmascarando el 75% de los parches de imagen. |
| `M5.7 Lab_autoencoders_JRSA.ipynb` | Laboratorio comparativo entre AE, DAE y VAE sobre Dogs vs Cats, manteniendo arquitectura y parámetros fijos entre los tres modelos. |

</details>

<details>
<summary><strong>Mario</strong> — Detección y segmentación (COCO)</summary>

| Archivo | Descripción |
| --- | --- |
| `Lab_COCO_JRSA.ipynb` | Entrenamiento y evaluación de modelos YOLO (detección de objetos y segmentación de instancias) sobre un subconjunto de COCO, con partición 70/15/15. |
| `Lab_COCO.docx` | Documento con las instrucciones/lineamientos del laboratorio. |

</details>

<details>
<summary><strong>Martín</strong> — TAE-IA: embeddings y transformers</summary>

| Archivo | Descripción |
| --- | --- |
| `M1-embeddings/lab-e-seq2seq-assignment.ipynb` | Tarea de seq2seq: traductor inglés→español con arquitectura encoder-decoder y atención, sobre el dataset Tatoeba. |
| `M2-transformers/lab-3-variants-assignament.ipynb` | Comparación de arquitecturas transformer (DistilBERT vs. GPT-2) para clasificación binaria de sentimiento en SST-2, ajustando distintos parámetros de fine-tuning. |

</details>
