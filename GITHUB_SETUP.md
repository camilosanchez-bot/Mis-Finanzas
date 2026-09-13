# 🚀 Cómo Montar Money-Flow en GitHub Pages

## ✅ Paso 1: Crea un repositorio en GitHub

1. Ve a [github.com](https://github.com)
2. Haz clic en el **+** arriba a la derecha
3. Selecciona **New repository**
4. Nombre del repositorio: `moneyflow-app`
5. Descripción: `Planificador de retiro Money-Flow - Método Claudia Uribe`
6. **Importante**: Selecciona **Public** (no Private)
7. Haz clic en **Create repository**

---

## ✅ Paso 2: Sube los archivos a GitHub

### Opción A: Desde la web (MÁS FÁCIL)

1. En la página de tu nuevo repositorio, haz clic en **Add file → Upload files**
2. **Arrastra estos archivos** desde tu computadora a GitHub:
   - `index.html` ← **ESTE ES EL MÁS IMPORTANTE**
   - `INSTRUCCIONES.md` (opcional)

3. En el cuadro "Commit message" escribe: `Agrega app Money-Flow`
4. Haz clic en **Commit changes**

### Opción B: Desde terminal (Si sabes Git)

```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/moneyflow-app.git
cd moneyflow-app

# Copia el index.html aquí
cp /ruta/a/index.html .

# Sube los cambios
git add index.html
git commit -m "Agrega app Money-Flow"
git push origin main
```

---

## ✅ Paso 3: Configura GitHub Pages

1. En tu repositorio, ve a **Settings** (arriba a la derecha)
2. En el menú izquierdo, busca **Pages**
3. En **Source**, selecciona:
   - Branch: `main`
   - Carpeta: `/ (root)`
4. Haz clic en **Save**

---

## ✅ Paso 4: ¡Tu app está viva!

GitHub Pages te mostrará un mensaje como:
```
Your site is published at https://TU_USUARIO.github.io/moneyflow-app/
```

**Espera 1-2 minutos** y abre ese link en tu navegador. ¡Verás tu app en vivo! 🎉

---

## 🔗 Tu URL será:
```
https://TU_USUARIO.github.io/moneyflow-app/
```

Cambia `TU_USUARIO` por tu usuario real de GitHub.

**Ejemplo:**
- Si tu usuario es `camilo`, tu link será:
- `https://camilo.github.io/moneyflow-app/`

---

## ✨ Prueba la app

Cuando abras el link:
1. Verás el formulario inicial
2. Ingresa tus datos (gasto, años, rentabilidad, etc.)
3. ¡Dale a "Comenzar Plan"!
4. Explora las 3 secciones

**Tus datos se guardan localmente** en tu navegador (no en servidores).

---

## 🔄 Actualizar la app

Si quieres hacer cambios:

1. Descarga el `index.html` actualizado
2. Sube a GitHub: **Add file → Upload files**
3. Reemplaza el archivo anterior
4. Commit: `Actualiza app Money-Flow`
5. En 1-2 minutos verás los cambios en tu link

---

## 📊 Compartir el link

Ahora puedes compartir tu app:
- 📱 En WhatsApp
- 📧 Por email
- 🔗 En tu bio
- 👥 Con amigos

¡Solo necesitan abrir el link, no instalar nada!

---

## ❌ Si algo no funciona

### "Solo veo las instrucciones"
- Espera 2-3 minutos más
- Recarga la página (F5 o Ctrl+R)
- Verifica que hayas subido **index.html** (no README.md)

### "La app no abre"
- Verifica que GitHub Pages esté habilitado en Settings → Pages
- Asegúrate de que el repositorio sea **Public** (no Private)
- Intenta en otro navegador

### "Mi link no funciona"
- Abre: `https://github.com/TU_USUARIO/moneyflow-app`
- Ve a Settings → Pages
- Verifica el link que te muestra
- Copia ese link exacto

---

## 🎓 Información técnica

- **Tecnología**: React 18 (desde CDN)
- **Base de datos**: localStorage (en tu navegador)
- **Hosting**: GitHub Pages (100% gratis)
- **Dominio**: github.io
- **Actualizaciones**: Instantáneas

---

## 💡 Opciones avanzadas

### Usar tu propio dominio
Si tienes un dominio (ej: miapp.com):
1. En **Settings → Pages → Custom domain**
2. Ingresa tu dominio
3. Sigue las instrucciones de DNS

### Desplegar en Vercel (más opciones)
1. Ve a [vercel.com](https://vercel.com)
2. Conecta tu GitHub
3. Elige el repositorio `moneyflow-app`
4. Vercel crea automáticamente el link

---

## ✅ Lista de verificación

Antes de compartir:
- [ ] Repositorio creado en GitHub
- [ ] `index.html` subido
- [ ] GitHub Pages habilitado en Settings
- [ ] Esperaste 2-3 minutos
- [ ] Link funciona y muestra la app
- [ ] Probaste con tus datos
- [ ] Compartiste con amigos 🎉

---

## 📞 ¿Necesitas ayuda?

1. Revisa la URL en tu navegador
2. Abre en **modo incógnito** (por si hay caché)
3. Intenta en otro navegador
4. Verifica que el repositorio sea **Public**

---

## 🚀 ¡Listo!

Tu app Money-Flow ya está en Internet. 

**Recuerda**: "No es lo que ganas, es lo que tu dinero genera cada mes."

¡Éxito con tu retiro! 💰✨
