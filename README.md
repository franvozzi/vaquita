<div align="center">
  <img src="/logo.png" alt="Vaquita Logo" width="400"/>
</div>

# Vaquita - Plataforma de Crowdfunding Basada en Criptomonedas

Vaquita es una plataforma de crowdfunding innovadora que utiliza tecnología blockchain para facilitar la recaudación de fondos de manera segura y transparente. Inspirado en el lunfardo argentino "Hagamos una vaquita", el proyecto busca combinar la facilidad del crowdfunding con la flexibilidad y seguridad de las criptomonedas.

## Tabla de Contenidos

- [Visión General](#visión-general)
- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Arquitectura](#arquitectura)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Visión General

Vaquita tiene como objetivo proporcionar una plataforma fácil de usar para proyectos que buscan financiarse a través de contribuciones en criptomonedas. Ofrece una interfaz intuitiva tanto para creadores de proyectos como para donantes, con el respaldo de contratos inteligentes para garantizar la transparencia y seguridad de las transacciones.

## Características

- **Creación de Proyectos:** Los usuarios pueden crear campañas de crowdfunding con descripciones detalladas, objetivos y plazos.
- **Contribuciones con Criptomonedas:** Soporte para diversas criptomonedas para contribuir a proyectos.
- **Transparencia y Seguridad:** Uso de contratos inteligentes para gestionar las contribuciones y asegurar el cumplimiento de las condiciones.
- **Interfaz Intuitiva:** Diseño de frontend amigable con React para una experiencia de usuario fluida.
- **Gestión de Usuarios:** Autenticación y autorización seguras utilizando JWT.
- **Visualización de Proyectos:** Listado y visualización de proyectos activos, en curso y finalizados.

## Tecnologías Utilizadas

- ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
- ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
- ![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
- ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
- ![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)
- ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## Arquitectura

El proyecto utiliza una arquitectura basada en microservicios para el backend, con una base de datos PostgreSQL para el almacenamiento de datos. Los contratos inteligentes en la blockchain de Ethereum gestionan las contribuciones y la transparencia. La aplicación frontend está construida con React y se comunica con el backend a través de una API REST.

## Instalación

### Prerrequisitos

- [Node.js](https://nodejs.org/) v16 o superior
- [PostgreSQL](https://www.postgresql.org/) v12 o superior
- [Truffle](https://www.trufflesuite.com/truffle) para contratos inteligentes
- [Ganache](https://www.trufflesuite.com/ganache) para pruebas en blockchain

### Clonación del Repositorio

```bash
git clone https://github.com/franvozzi/vaquita.git
cd vaquita
```
## Instalación de Dependencias
### Instalación de dependencias del frontend
```bash
cd frontend
npm install
```

### Instalación de dependencias del backend
```bash
cd ../backend
npm install
```

### Configuración del Entorno
Copia el archivo de ejemplo de configuración y ajusta las variables:
```bash
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```
Edita los archivos .env para incluir la configuración de tu base de datos y API keys.

### Iniciar el frontend
```bash
cd frontend
npm start
```

### Iniciar el backend
```bash
cd ../backend
npm start
```

## Uso
Crear una Cuenta: Regístrate en la plataforma para crear y gestionar proyectos.
Crear un Proyecto: Completa los detalles del proyecto y publica para recibir contribuciones.
Contribuir a un Proyecto: Navega por los proyectos disponibles y contribuye con criptomonedas.
Monitorear Contribuciones: Revisa el estado de las contribuciones y el progreso del proyecto.

## Contribución
Las contribuciones son bienvenidas. Para contribuir al proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una rama para tu feature o bugfix (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y confirma (git commit -am 'Añadir nueva funcionalidad').
Empuja la rama al repositorio remoto (git push origin feature/nueva-funcionalidad).
Crea un pull request en GitHub.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.

## Contacto
Francisco Vozzi - franciscovozzi@outlook.com
GitHub: franvozzi
¡Gracias por tu interés en Vaquita! Esperamos que encuentres útil y emocionante esta plataforma de crowdfunding basada en criptomonedas.

Este `README.md` proporciona una visión general del proyecto, detalles sobre su instalación y uso, y cómo contribuir. Asegúrate de personalizar cualquier detalle específico según avance el desarrollo del proyecto.
