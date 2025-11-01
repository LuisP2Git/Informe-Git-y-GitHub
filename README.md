# README.md — Uso básico de Git y GitHub

## 🔹 Introducción
En este informe explico de forma sencilla los **comandos más usados de Git** y el **proceso para subir cambios a GitHub**.  
Todo está basado en los videos vistos y la documentación oficial, pero explicado con mis palabras.

---

## 🧰 Comandos principales de Git

| Comando | Explicación breve |
|----------|------------------|
| `git init` | Inicia un repositorio en la carpeta actual. |
| `git status` | Muestra los cambios pendientes o nuevos. |
| `git add .` | Agrega todos los archivos para el commit. |
| `git commit -m "mensaje"` | Guarda los cambios con una descripción. |
| `git branch` | Muestra o crea ramas del proyecto. |
| `git remote add origin <url>` | Conecta el repositorio local con GitHub. |
| `git push -u origin main` | Envía los cambios al repositorio remoto. |
| `git pull origin main` | Trae los cambios desde GitHub a tu carpeta local. |
| `git clone <url>` | Descarga un repositorio completo desde GitHub. |

---

## 🚀 Pasos para subir tus cambios a GitHub

1. **Crear o entrar a la carpeta del proyecto**
   ```bash
   cd ruta/de/mi/proyecto
   ```

2. **Inicializar Git**
   ```bash
   git init
   ```

3. **Agregar los archivos**
   ```bash
   git add .
   ```

4. **Hacer el commit**
   ```bash
   git commit -m "Primer commit"
   ```

5. **Crear el repositorio en GitHub**
   - Ir a [github.com](https://github.com) → *New Repository* → ponerle nombre y crear.

6. **Vincular el remoto**
   ```bash
   git remote add origin https://github.com/tuusuario/nombre-repo.git
   ```

7. **Subir los cambios**
   ```bash
   git push -u origin main
   ```

8. **Verificar en GitHub**  
   Abre tu repositorio y revisa que aparezcan los archivos.

---

## 🖼️ Capturas de evidencia

Guarda las capturas en una carpeta llamada **`images/`** y agrégalas así:

```markdown
![Inicialización de Git](images/paso1-init.png)
![Commit realizado](images/paso2-commit.png)
![Repositorio en GitHub](images/paso3-github.png)
```

---

## 🧩 Ejemplo completo de comandos

```bash
git init
git add .
git commit -m "Agrego README con explicación"
git remote add origin https://github.com/tuusuario/mi-repo.git
git branch -M main
git push -u origin main
```

---

## 📘 Referencias
- Videos sobre Git y GitHub (YouTube).  
- Guía oficial de GitHub sobre escritura y formato.  
- Documentación de Markdown.  
