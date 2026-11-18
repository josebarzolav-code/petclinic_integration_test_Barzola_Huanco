# Laboratorio 14: análisis con SonarQube

Este repositorio contiene el proyecto PetClinic utilizado como código de entrada para el análisis estático del laboratorio. El trabajo del laboratorio se realizó en la rama `lab14-sonarqube`; `main` se mantuvo sin cambios.

## Trabajo realizado

- Se preparó una instancia EC2 Ubuntu 22.04 con Java 21, PostgreSQL 14, SonarQube Community Build 26.11 y Nginx.
- Se ejecutaron las pruebas Maven: **27 aprobadas, 0 fallos y 0 errores**.
- El análisis Maven se cargó en SonarQube en el proyecto **PetClinic** (`petclinic-lab`).
- Se revisó el panel de resultados y el estado del Quality Gate.

## Resultados del análisis

- **Quality Gate:** Passed.
- **Hallazgos:** 5 en total: 1 de seguridad, 0 de fiabilidad y 4 de mantenibilidad.
- **Cobertura:** 0.0%; este análisis no importó un informe de cobertura.
- **Duplicaciones:** 0.0%.

Quality Gate Passed no significa que el proyecto esté libre de hallazgos; los cinco resultados deben revisarse en el panel.

## Entregables

- [Informe de desarrollo](./GLAB-S14-JFARFAN-2026-02_Desarrollo.docx)
- [Documento de evidencias](./GLAB-S14-JFARFAN-2026-02_Evidencias.docx)

GitHub no previsualiza los documentos Word en la vista de cambios; abre cada enlace para descargarlos.

## Git

- Repositorio: [petclinic_integration_test_Barzola_Huanco](https://github.com/josebarzolav-code/petclinic_integration_test_Barzola_Huanco)
- Rama de trabajo: `lab14-sonarqube`
- Tag publicado: `lab14-sonarqube-v1`

El repositorio contiene el código fuente usado para la práctica y los entregables del laboratorio. No se modificó el código fuente de PetClinic; la práctica consistió en ejecutarlo, analizarlo y documentar los resultados.
