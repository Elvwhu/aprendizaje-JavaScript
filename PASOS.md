# 🚀 Pasos para actualizar el repositorio

Este archivo explica el proceso para actualizar tu repositorio en GitHub con nuevos cambios. Sigue estos pasos cada vez que quieras subir tus avances:

---

## 1. **Asegúrate de estar en la carpeta del repositorio**
   - Abre la terminal y navega hasta la carpeta del repositorio:
     ```bash
     cd ruta/del/repositorio
     ```

---

## 2. **Verifica el estado del repositorio**
   - Comprueba los archivos que han cambiado o que no están agregados:
     ```bash
     git status
     ```

---

## 3. **Agrega los archivos modificados**
   - Para agregar todos los cambios:
     ```bash
     git add .
     ```
   - O agrega un archivo específico:
     ```bash
     git add nombre-del-archivo
     ```

---

## 4. **Confirma los cambios**
   - Crea un mensaje descriptivo para tu cambio:
     ```bash
     git commit -m "Descripción breve del cambio realizado"
     ```

---

## 5. **Sube los cambios al repositorio remoto**
   - Envía los cambios a GitHub:
     ```bash
     git push origin main
     ```
   - Si tu rama principal tiene otro nombre (por ejemplo, `master`), usa:
     ```bash
     git push origin master
     ```

---

## 6. **Confirma que los cambios se reflejaron**
   - Ve a tu repositorio en GitHub y revisa que los cambios se hayan subido correctamente.

---

## ❗ Notas importantes
- Si clonas un repositorio en otro equipo o vuelves después de un tiempo, es recomendable sincronizar los cambios antes de trabajar:
  ```bash
  git pull origin main
