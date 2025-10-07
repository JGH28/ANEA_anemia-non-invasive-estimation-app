# Universidad de Guadalajara

## Centro Universitario de Ciencias Exactas e Ingenierías

### Ingeniería Biomédica

### Proyecto Modular: 
### ANEA: Anemia Non-Invasive Estimation App

### Asesor: Dr. Omar Paredes

### Co-Asesor: Mtro. Moisés Sotelo Rodríguez

### Integrantes del equipo:

* Sael Cardona Noriega - sael.cardona2597@alumnos.udg.mx
* José de Jesús González Hernández - jose.gonzalez0672@alumnos.udg.mx
* Marisol Elizabeth Huerta Lucio - marisol.huerta4198@alumnos.udg.mx
---
## ANEA: Anemia Non-Invasive Estimation App

## Objetivo del Proyecto

**ANEA** tiene como objetivo desarrollar una herramienta basada en inteligencia artificial que permita segmentar automáticamente la región de la conjuntiva palpebral a partir de una imagen del ojo, como paso previo para estimar el nivel de hemoglobina en sangre y, por ende, detectar posibles casos de anemia de forma no invasiva.


## Fases del Proyecto

- **Fase 1 – Segmentación de la conjuntiva palpebral**
    - Desarrollo de un modelo de segmentación (basado en Transformers) que identifica la región de interés en imágenes del ojo.
- **Fase 2 – Desarrollo de la aplicación web**
    - Diseño de una plataforma interactiva que permite al usuario cargar una foto y recibir su análisis.
- **Fase 3 – Validación clínica**
    - Recolección de imágenes y niveles de hemoglobina de pacientes mexicanos para validar el sistema.

## Tecnologías

- Python, PyTorch, Hugging Face Transformers
- Google Colab
- Makesense.ai (etiquetado)
- GitHub, Google Drive

## Estructura del Repositorio

```
ANEA/
├── fase_1_segmentacion/
│   ├── Model_Palpebral_Segmentation_finetuned.ipynb
│   ├── README.md        ← Descripción detallada de esta fase
│   ├── requirements.txt
├── fase_2_app/          ← (por desarrollar)
├── fase_3_validacion/   ← (por desarrollar)
└── README.md            ← Este archivo
```

## Nota:

El dataset base no se incluye por razones de derechos de uso. Solo se comparten scripts, notebooks y documentación.
