# Zoologico-colaborativo-Python 🐍

### *Aprende Git y Python colaborando… y sobreviviendo a los conflictos de merge*

Bienvenid@ al **Python & Git Chaos Challenge**, un ejercicio diseñado para que aprendas Git y Python de forma práctica, rápida y divertida.  Aquí no buscamos perfección: buscamos **conflictos**, **errores**, **pulls que rompen cosas**, y sobre todo, **aprender haciendo**.
 
Prepárate para el caos.

---

## 🎯 Objetivo del ejercicio
Aprender:

- Cómo hacer **commits**
- Cómo hacer `git pull` y `git push`
- Qué es un **conflicto de merge** y cómo resolverlo
- Cómo colaborar en un archivo Python compartido
- Cómo sobrevivir cuando muchas personas editan la misma línea

---
## 🧪 Fase 1: Caos sin ramas

En esta primera parte **todos trabajan directamente en `main`**.  
La idea es que editen la misma línea y provoquen conflictos inmediatos.

### Pasos

- Clona el repositorio.  
- Edita `animals.py` y añade tu animal:  

  ```python
  animals.append("Tigre de Ana")
  ```
- Guarda el archivo, haz commit y push

---

### ¿Qué ocurre aquí?

Cuando varias personas hagan esto al mismo tiempo, los conflictos aparecerán.  
Aquí aprenderás a:  
- Hacer `git pull`  
- Resolver conflictos en tu editor (VSCode o GitHub)  
- Entender por qué ocurre  

---

## 🧨 Fase 2: Orden con ramas

Después de haber vivido el caos en `main`, llega el momento de trabajar de forma más organizada.  
Cada persona debe crear **una rama de trabajo** y luego abrir un Pull Request para integrar sus cambios.

### 🎓 Qué aprenderás aquí

- Que los conflictos no desaparecen, pero se gestionan mejor.
- Cómo usar ramas para aislar tu trabajo y evitar romper `main`.
- Cómo colaborar mediante Pull Requests y revisiones.
- Cómo resolver conflictos de merge en tu editor y dejar el historial más limpio y entendible.
- Cómo se ve un conflicto real y cómo se transforma en un archivo limpio después de resolverlo.

### Buenas prácticas al crear ramas

- Usa un prefijo que indique el tipo de trabajo (por ejemplo: `feature/`, `fix/`, `chore/`).  
- Evita nombres genéricos o personales como `juan` o `ana`.  
- Nombra la rama según lo que haces:  

  Ejemplos correctos:  
  - `feature/add-tigre-ana`  
  - `feature/add-perro-juan`  
  - `feature/add-gato-laura`

### Pasos

1. **Crear una rama de trabajo**  
   ```bash
   git checkout -b feature/add-tigre-ana
   ```
2. **Editar `animals.py` y añadir tu animal**
3. **Hacer commit y push**
4. **Abrir un Pull Request en GitHub**

   - Describe claramente qué animal añadiste.
   - Usa un título descriptivo: `“Añadir Tigre de Ana a la lista de animales”`.
   - Espera la revisión y merge.


### Cómo se ven los conflictos de merge 🛠️
Cuando dos ramas modifican la misma parte del archivo, Git no sabe cuál versión conservar. El archivo se marca con secciones especiales:

![texto opcional](https://imgs.search.brave.com/oltxmAdRKtEyr21tMyg6gXGp_q4ULvQTlHklQx5gInk/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9kb2Nz/LnBhbnRoZW9uLmlv/L19uZXh0L3N0YXRp/Yy9tZWRpYS92c2Nv/ZGUtbWVyZ2UtY29u/ZmxpY3QuOGNhYTU1/YjAucG5n)

- **Current change (HEAD)** → lo que tienes en tu rama local. 
- **Incoming change** → lo que viene de la otra rama que intentas fusionar.

Tu tarea es decidir qué líneas mantener, combinarlas si hace falta, y luego guardar el archivo. Después harás un commit para confirmar la resolución del conflicto.


---

### 🎉 Happy Learning & Data Exploring 📊🐍

Has visto cómo el caos inicial en `main` genera conflictos y cómo las ramas y Pull Requests ayudan a gestionarlos mejor.  
Ahora ya sabes: **los conflictos son parte natural del trabajo colaborativo, y resolverlos te hace crecer como analista de datos.**  

Sigue practicando, sigue colaborando y recuerda: cada conflicto resuelto es un paso más hacia dominar Git y trabajar en equipo en proyectos.

--- 

📅 Última actualización: Febrero 2026
