# Desafío Académico de Métodos Numéricos: GCP en Ingeniería de Sistemas, Método del Gradiente

Repositorio oficial para el desarrollo del Desafío Académico de Métodos Numéricos de la Carrera de Informática (Facultad de Ciencias Puras y Naturales - FCPN), Universidad Mayor de San Andrés (UMSA).

* **Estudiante:** Cristian Alexander Quispe Espinal
* **Mención:** Ingeniería de Sistemas
* **Área:** Planificación Financiera y Distribución de Recursos Institucionales

---

## 1. Descripción del Proyecto
Este proyecto implementa y modela la distribución óptima de recursos presupuestarios y flujos de caja interdepartamentales entre cuatro unidades organizacionales de TI ($n \ge 4$) mediante el **Método de Gradientes Conjugados Precondicionado (GCP)**.

Toda la fundamentación teórica, el modelado matemático, la solución de referencia, la ejecución iterativa paso a paso, los análisis de error por componente y el módulo de control de calidad (QA) se encuentran integrados de forma orgánica e interactiva dentro de una **página web funcional de acceso público**.

---

## 2. Instrucciones de uso
Para hacer uso de la página simplemente clone el repositorio e ingrese al archivo index.html, se abrirá la página y podrá ver tres ejemplos de escenarios, además de que podrá modificar los datos del ejercicio y para resolverlos debe presionar en el botón "Ejecutar Algoritmo GCP", el ejercicio se resolverá de forma automática y podrá ver los detalles del mismo en la misma página.
De igual forma puede ingresar a la página mediante este link: 

---

## 3. Arquitectura del Repositorio
El repositorio está estructurado en la raíz con un diseño minimalista y autocontenido para facilitar su despliegue inmediato en plataformas estáticas (como GitHub Pages, Vercel o Netlify):

```text
├── index.html        # Aplicación web interactiva completa (HTML5, Tailwind CSS y JavaScript vainilla)
└── README.md         # Documentación técnica del proyecto y guía de instalación
