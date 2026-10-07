# Tarjeta de Presentación Digital — Itxaso Gurrea

Tarjeta de presentación web interactiva, moderna y optimizada para dispositivos móviles, diseñada para compartir de forma ágil mediante enlace directo o código QR.

## 📱 Características Principales

1. **Guardar Contacto en 1 Clic**:
   - Botón principal que genera y descarga al instante el archivo estándar `Itxaso_Gurrea.vcf` (vCard 3.0).
   - Compatible nativamente con **iPhone (Apple Contacts)**, **Android (Google Contacts)** y clientes de escritorio.

2. **Acciones Rápidas Directas**:
   - **WhatsApp**: Abre chat directo con saludo preconfigurado al número `+34617308517`.
   - **Llamar**: Conecta la llamada directa `tel:+34617308517`.
   - **Email**: Abre el gestor de correo listo para escribir a `itxasogurrea@gamil.com`.

3. **Enlaces Profesionales**:
   - Enlace directo al **Sitio Web Oficial**: [www.itxasocoach.com](https://www.itxasocoach.com)
   - Acceso al perfil de **LinkedIn**: [linkedin.com/in/itxasogurrea](https://www.linkedin.com/in/itxasogurrea)
   - Perfil de **Instagram**: [@itxaso_gurrea](https://instagram.com/itxaso_gurrea)

4. **Herramientas de Difusión**:
   - **Botón Compartir**: Usa la API nativa de compartir del móvil o copia el enlace al portapapeles.
   - **Modal de Código QR**: Genera en pantalla el QR de la tarjeta para que cualquier persona frente a ti pueda escanearla al instante con su cámara.

---

## 🖼️ Cómo sustituir las iniciales "IG" por tu foto real

En el archivo `index.html` (alrededor de la línea 320):

1. Coloca tu archivo de fotografía (por ejemplo `foto-itxaso.jpg`) en la misma carpeta que `index.html`.
2. Busca este bloque en `index.html`:
   ```html
   <div class="avatar">
     <span class="avatar-initials" id="avatar-initials">IG</span>
     <img src="" alt="Itxaso Gurrea" class="avatar-image" id="avatar-photo">
   </div>
   ```
3. Cámbialo simplemente por:
   ```html
   <div class="avatar">
     <img src="foto-itxaso.jpg" alt="Itxaso Gurrea" class="avatar-image" id="avatar-photo" style="display:block;">
   </div>
   ```

---

## 🌐 Cómo publicarla en Internet de forma gratuita

Puedes publicar este archivo en cuestión de 2 minutos para tener tu propio enlace (por ejemplo `itxaso.github.io` o tu propio dominio):

### Opción recomendada: GitHub Pages
1. Sube este repositorio a GitHub.
2. En GitHub ve a **Settings** > **Pages**.
3. En **Branch**, selecciona `main` (o `master`) y guarda (**Save**).
4. ¡Listo! En 1 minuto tendrás tu enlace público accesible para todo el mundo.
