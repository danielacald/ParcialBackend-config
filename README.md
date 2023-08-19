# Repositorio de Configuraciones para Examen Parcial - Especialización Backend II

Este repositorio contiene las configuraciones en formato `.yml` para varios microservicios como parte del examen parcial de la materia Especialización Backend II. 

## Equipo
- Alberto Gómez Juan 
- Daniela Calderón.

## Estructura del Repositorio


```
config-service/
│
├── catalog-service/
│ └── application.yml
│
├── movie-service/
│ └── application.yml
│
├── eureka-server/
│ └── application.yml
│
└── api-gateway/
  └── application.yml
```

Cada microservicio tiene su propia carpeta que contiene los archivos `.yml` necesarios para su configuración. Además, hay una carpeta para el `eureka-server` y otra para el `api-gateway`.

## Configuraciones Centrales

Este repositorio sirve como fuente centralizada de configuraciones para los microservicios. Cada archivo `.yml` contiene propiedades específicas para cada microservicio y se accede de manera automática durante la inicialización de los servicios.


## Profesora
- Vanina Godoy