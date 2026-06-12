# Plataforma de Chat Web - Frontend

Este repositorio contiene el codigo de la interfaz de usuario para la aplicacion web de comunicacion en tiempo real inspirada en la arquitectura de Discord. El desarrollo se realiza de forma conjunta por dos programadores con el objetivo de simular un entorno de trabajo profesional.

## Tecnologias utilizadas

* Framework: React (Vite)
* Estilos: Tailwind CSS
* Conexion en tiempo real: Socket.io-client
* Gestion de tareas: GitHub Projects

## Flujo de trabajo del equipo

1. Proteccion de ramas: La rama main esta protegida. Ningun desarrollador puede realizar push directo a ella.
2. Revision de codigo: Todo cambio requiere la creacion de un Pull Request y la aprobacion obligatoria del otro miembro del equipo antes de ser fusionado.
3. Organizacion: El desarrollo se gestiona mediante un tablero Kanban basado en historias de usuario y tickets.

## Instalacion y configuracion local

Siga estos pasos para ejecutar el proyecto en un entorno local:

1. Clone este repositorio:
   git clone https://github.com/ORGANIZACION/repo-frontend.git

2. Acceda al directorio del proyecto:
   cd repo-frontend

3. Instale las dependencias del sistema:
   npm install

4. Cree un archivo .env en la raiz del proyecto tomando como referencia el archivo .env.example, y configure la url del backend:
   VITE_API_URL=http://localhost:5000

5. Inicie el servidor de desarrollo:
   npm run dev

## Autores

* Desarrollador 1: https://github.com/CatalinDP
* Desarrollador 2: https://github.com/Joaquincg200
* Desarrollador 2: https://github.com/JosePujanteDev
