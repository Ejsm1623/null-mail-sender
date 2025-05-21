# NullMail Sender

NullMail Sender es una aplicación web construida con [Astro](https://astro.build/) que simula el envío de correos electrónicos a través de un formulario simple, directo y validado. Ideal para pruebas de UI, demostraciones o como base para proyectos de mailing.

## 🚀 Características

- **Simulación de envío de correos:** El formulario valida y simula el envío de emails, mostrando mensajes de éxito y errores.
- **Validación de campos:** Verifica que el correo electrónico sea válido, el asunto tenga al menos 5 caracteres y el mensaje mínimo 10 caracteres.
- **Interfaz simple y directa:** Solo los campos necesarios: destinatario, copia (CC), asunto y mensaje.
- **Estilos modernos:** Utiliza TailwindCSS y fuentes personalizadas.

## 📁 Estructura del Proyecto

```
/
├── public/
│   ├── favicon.svg
│   ├── Hero.png
│   ├── MailPattern.png
│   └── fonts/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── FeatureCard.astro
│   │   ├── FormButton.astro
│   │   ├── MessageField.astro
│   │   └── StandardField.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── package.json
└── astro.config.mjs
```

## 🧑‍💻 Instalación y uso

1. **Clona el repositorio:**

   ```sh
   git clone https://github.com/tu-usuario/null-mail-sender.git
   cd null-mail-sender
   ```

2. **Instala las dependencias:**

   ```sh
   npm install
   ```

3. **Inicia el servidor de desarrollo:**

   ```sh
   npm run dev
   ```

   El sitio estará disponible en [http://localhost:4321](http://localhost:4321).

4. **Compila para producción:**

   ```sh
   npm run build
   ```

5. **Previsualiza la build:**

   ```sh
   npm run preview
   ```

## 📝 Personalización

- Puedes modificar los estilos en [`src/styles/global.css`](src/styles/global.css).
- Los componentes del formulario se encuentran en [`src/components/`](src/components/).
- La lógica de validación y simulación está en [`src/pages/index.astro`](src/pages/index.astro).

## 📦 Tecnologías utilizadas

- [Astro](https://astro.build/)
- [TailwindCSS](https://tailwindcss.com/)
- HTML, CSS, JavaScript

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

---

¡Disfruta usando NullMail Sender! Si tienes sugerencias o encuentras algún problema, no dudes en abrir un issue o un pull request.
