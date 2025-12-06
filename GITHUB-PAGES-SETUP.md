# 🚀 Configurar GitHub Pages

## Pasos para Publicar tu Página

### 1. Activar GitHub Pages

1. Ve a tu repositorio en GitHub: `https://github.com/Vlkair/PaginaWeb-cliente`

2. Haz clic en **Settings** (Configuración) en el menú superior

3. En el menú lateral izquierdo, busca y haz clic en **Pages**

4. En la sección **Source** (Fuente):
   - Selecciona **Deploy from a branch**
   - En **Branch**, selecciona: `main`
   - En la carpeta, selecciona: `/ (root)`
   - Haz clic en **Save**

5. ¡Espera 1-2 minutos! GitHub construirá tu sitio automáticamente

6. Tu página estará disponible en:
   ```
   https://vlkair.github.io/PaginaWeb-cliente/
   ```

### 2. Verificar que Funciona

- Regresa a **Settings > Pages**
- Verás un mensaje verde que dice: "Your site is live at..."
- Haz clic en **Visit site** o copia la URL

### 3. Para Editar y Actualizar

Cada vez que quieras hacer cambios:

```bash
# 1. Edita tus archivos (index.html, css/styles.css, etc.)

# 2. Guarda los cambios en git
git add .
git commit -m "Descripción de tus cambios"

# 3. Sube a GitHub
git push origin main

# 4. ¡GitHub Pages se actualizará automáticamente en 1-2 minutos!
```

## 📝 Comandos Git Útiles

### Verificar estado
```bash
git status
```

### Ver cambios
```bash
git diff
```

### Agregar archivos específicos
```bash
git add index.html
git add css/styles.css
```

### Hacer commit con mensaje descriptivo
```bash
git commit -m "Actualizar colores del header"
git commit -m "Agregar nueva sección de testimonios"
git commit -m "Cambiar imágenes de proyectos"
```

### Subir cambios
```bash
git push origin main
```

### Ver historial de commits
```bash
git log --oneline
```

## 🎨 Flujo de Trabajo Recomendado

### Para cambios pequeños (colores, textos):
```bash
# 1. Edita el archivo
# 2. Guarda
git add .
git commit -m "Cambiar color principal a azul"
git push origin main
```

### Para cambios grandes (nueva sección):
```bash
# 1. Edita varios archivos
# 2. Prueba localmente
# 3. Guarda todo
git add .
git commit -m "Agregar sección de testimonios con estilos y funcionalidad"
git push origin main
```

## 🔄 Actualización Automática

- ✅ Cada `git push` actualiza tu sitio automáticamente
- ⏱️ Los cambios tardan 1-2 minutos en verse
- 🔄 Refresca la página con `Ctrl + F5` para ver los cambios
- 📱 Limpia caché del navegador si no ves actualizaciones

## 🐛 Solución de Problemas

### Mi página no carga
- Verifica que `index.html` esté en la raíz del repositorio
- Asegúrate de que GitHub Pages esté activado
- Espera 2-3 minutos después del primer push

### Los cambios no se ven
- Limpia el caché: `Ctrl + Shift + R` (Windows) o `Cmd + Shift + R` (Mac)
- Verifica que hiciste `git push origin main`
- Espera 1-2 minutos para que GitHub actualice

### Error al hacer push
```bash
# Si hay conflictos, primero haz pull
git pull origin main
# Luego push
git push origin main
```

## 📱 Compartir tu Sitio

Tu URL pública es:
```
https://vlkair.github.io/PaginaWeb-cliente/
```

Compártela en:
- Redes sociales
- Tarjetas de presentación
- Email
- WhatsApp

## 🎯 Próximos Pasos

1. ✅ Activa GitHub Pages (sigue los pasos arriba)
2. ✅ Verifica que tu sitio funcione
3. ✅ Personaliza el contenido gradualmente
4. ✅ Haz commit de cada cambio
5. ✅ Comparte tu URL

## 💡 Tips

- Haz commits frecuentes con mensajes descriptivos
- Prueba los cambios localmente antes de hacer push
- Usa nombres de commit claros: "Cambiar logo" mejor que "update"
- Guarda cambios relacionados en un mismo commit

---

**¡Tu sitio estará en línea en minutos! 🎉**
