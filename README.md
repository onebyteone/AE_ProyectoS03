# 🤝 Cómo colaborar usando Visual Studio Code

Este documento explica cómo clonar el repositorio y contribuir utilizando **Visual Studio Code** y **Git**.

## 📎 Enlace del repositorio

```bash
https://github.com/onebyteone/AE_ProyectoS03.git
````

---

## 📥 Clonar el repositorio

1. Abre **Visual Studio Code**.
2. Presiona `Ctrl + Shift + P` para abrir la paleta de comandos.
3. Escribe `Git: Clone` y presiona `Enter`.
4. Pega el enlace del repositorio:
   `https://github.com/onebyteone/AE_ProyectoS03.git`
5. Elige la carpeta donde deseas guardar el proyecto localmente.
6. Selecciona **"Abrir"** o **"Abrir en una nueva ventana"** cuando se complete la clonación.

---

## ✏️ Realizar cambios

1. Haz tus modificaciones en el código.
2. Guarda los archivos (`Ctrl + S`).
3. Abre la pestaña **Source Control** (ícono de ramificación en la barra lateral izquierda).
4. Verás una lista de archivos modificados.
5. Haz clic en el ícono **➕** junto a cada archivo para agregarlos al área de *Staged Changes*.
6. Escribe un mensaje de *commit* en el campo superior (describiendo los cambios realizados).
7. Haz clic en el botón desplegable de **Commit** y selecciona **Commit & Push** para subir los cambios al repositorio remoto.

---

## ✅ Recomendaciones

* Asegúrate de hacer **pull** antes de hacer **push** para evitar conflictos:
  Ve a la paleta de comandos (`Ctrl + Shift + P`) → `Git: Pull`.

* Utiliza **ramas** si vas a hacer cambios grandes:

  ```bash
  git checkout -b nombre-de-tu-rama
  ```

* Los mensajes de *commit* deben ser claros y descriptivos.

---

¿Dudas o errores? Revisa la pestaña **Output** o el **Terminal** en VS Code para más información.

---
