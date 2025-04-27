# Introducción a GCP

[Google Cloud Plataform](https://cloud.google.com/?) (GCP)  es una serie de servicios de 
Google en lanube para acceder a recursos como
máquinas virtuales, servicios de bases de datos, almacenamiento, etc. Con diferentes
niveles de abstracciones y destinado a ayudar al despliegue y mantenimiento de aplicaciones
computaciobales de todo tipo.

## Apectos básicos de GCP

GCP clasifica los servicios en cinco grande grupos: Compute (computación o procesamiento), Storage (almacenamiento), Big Data, Machine Learning y Aplicaction Services (servicios para aplicaciones). 

Según el IEEE se define "computación en la nube" como un modelo que permite el acceso a una red bajo demanda de un conjunto de servicios informáticos configurables, como infraestructura, aplicaciones y almacenamiento.

GCP está dividido en "Ubicaciones geográficas" -> "Regiones" -> "Zonas" de froma jerárquica. Por ejemplo la región europe-west2 de lodres tiene 3 zonas: europe-west2-a, europe-west2-b y europe-west2-c; y a su vez su ubicación geográfica es Europa. El uso de múltiples recursos en diferentes zonas de la misma región ayuda a tener mejor tolerancia a fallos por redundancia.