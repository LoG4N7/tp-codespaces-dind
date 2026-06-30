# TP: Servidor de Pruebas Docker in Docker (DinD) en GitHub Codespaces

## Datos del Alumno
* **Nombre y Apellido:** Demian Thaiel Molina
* **DNI:** 44769256
* **Carrera:** Tecnicatura en Seguridad Informática
* **Materia:** Servidores
* **Institución:** Universidad Católica de Salta

---

## Descripción del Proyecto
Este proyecto consiste en el diseño, configuración y despliegue de un entorno de desarrollo basado en la nube utilizando **GitHub Codespaces**. El objetivo principal de la práctica es configurar un *workspace* virtualizado mediante un modelo de Plataforma como Servicio (PaaS) que permita ejecutar un servidor de pruebas **Docker in Docker (DinD)**.

A través de la definición de un contenedor de desarrollo personalizado (`.devcontainer.json`), se habilita la capacidad de levantar un demonio de Docker aislado dentro del propio entorno virtual. Esto permite realizar pruebas de despliegue, testing de microservicios y prácticas de contenedores de manera segura y eficiente en la nube, sin consumir recursos locales ni comprometer la seguridad del sistema host.

---

## Estructura del Repositorio
* `.devcontainer/`
  * `devcontainer.json`: Archivo de configuración que especifica la imagen base (Ubuntu) y la característica (*Feature*) oficial para habilitar el motor de Docker interno de forma aislada.
* `README.md`: Presentación de los datos del alumno y alcance del trabajo práctico.
