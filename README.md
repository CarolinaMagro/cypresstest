
# PageObjectModel 🚀

Este repositorio contiene un proyecto de pruebas automatizadas utilizando **Cypress** con el patrón de diseño **Page Object Model (POM)**. El objetivo de este proyecto es estructurar las pruebas de una manera que facilite su mantenimiento y escalabilidad, permitiendo realizar pruebas de manera eficiente y organizada.

## Tabla de Contenidos 📑

- [Estructura del Proyecto](#estructura-del-proyecto)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Ejecución de Pruebas](#ejecución-de-pruebas)
- [Generación de Reportes](#generación-de-reportes)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Estructura del Proyecto 🗂️

El proyecto está organizado en los siguientes directorios y archivos:

- **.git/**: Carpeta de control de versiones Git.
- **cypress/**: Contiene las pruebas automatizadas utilizando Cypress y las implementaciones del patrón Page Object Model.
- **node_modules/**: Directorio donde se encuentran las dependencias de Node.js instaladas.
- **cucumber-html-report/**: Reportes generados en formato HTML por Cucumber.
- **package.json**: Archivo de configuración del proyecto que incluye las dependencias y scripts necesarios.
- **package-lock.json**: Archivo que asegura la consistencia de las dependencias instaladas.

## Requisitos ⚙️

Para ejecutar este proyecto, necesitarás:

- Node.js y npm 🟢
- Cypress 🧪
- Cucumber para generación de reportes 📊

## Instalación 💻

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. Clona el repositorio:

    ```bash
    git clone <URL-del-repositorio>
    cd PageObjectModel
    ```

2. Instala las dependencias del proyecto:

    ```bash
    npm install
    ```

## Configuración 🛠️

1. Asegúrate de que todos los archivos de configuración necesarios estén en su lugar.
2. Configura las variables de entorno o modifica los archivos de configuración según sea necesario para tu entorno.

## Ejecución de Pruebas 🧪

Para ejecutar las pruebas automatizadas, utiliza el siguiente comando:

```bash
npx cypress open
```

Este comando abrirá la interfaz de Cypress donde podrás ejecutar las pruebas de manera interactiva.

Para ejecutar las pruebas en modo headless:

```bash
npx cypress run
```

## Generación de Reportes 📊

Después de ejecutar las pruebas, los reportes se generarán automáticamente en el directorio `cucumber-html-report/`. Puedes abrir estos archivos para ver los resultados detallados.

## Contribuir 🤝

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza los cambios necesarios y haz commits (`git commit -m 'Agrega nueva funcionalidad'`).
4. Empuja los cambios a la rama (`git push origin feature/nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia 📄

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo `LICENSE`.
