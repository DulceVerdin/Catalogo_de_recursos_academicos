Catálogo de recursos académicos

Descripción

Catálogo de recursos académicos es un proyecto que representa la estructura inicial de un sistema para registrar y consultar diferentes recursos educativos. Entre los recursos que puede manejar se encuentran libros, sitios web, videos, artículos y herramientas de software.

Objetivo

Crear la estructura inicial de un sistema que permita organizar recursos académicos y que posteriormente pueda utilizarse para registrar, consultar y clasificar información educativa.

Estructura del proyecto

catalogo_recursos/
│
├── app/
│   ├── main.py
│   └── configuracion.py
│
├── data/
│   └── recursos.json
│
├── docs/
│   ├── alcance.md
│   ├── criterios.md
│   ├── respuestas.md
│   ├── fuentes_recomendadas.md
│   └── evidencias/
│
├── tests/
│   └── test_basico.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── CHANGELOG.md


Tecnologías utilizadas

 Python
 Visual Studio Code
 Git
 GitHub
 JSON
 GitHub Pull Requests

 Preparación del entorno

 Crear y abrir la carpeta del proyecto en Visual Studio Code.
 Crear un entorno virtual llamado ".venv "
 Activar el entorno virtual.
 Instalar las dependencias del proyecto.
 Verificar que Python y las dependencias funcionen correctamente.

#Dependencias

Las dependencias utilizadas en el proyecto son:

*requests
*rich

Estas dependencias se encuentran registradas en el archivo "requirements.txt".

Próximas mejoras

 Agregar nuevos tipos de recursos académicos.
 Permitir búsquedas por tema.
 Agregar filtros por nivel académico.
 Permitir modificar y eliminar recursos.
 Crear una interfaz para consultar el catálogo.

 Tipos de recursos

El catálogo puede manejar diferentes tipos de recursos académicos, entre ellos:

 Libros.
 Sitios web.
 Videos.
 Artículos.
 Herramientas de software.
