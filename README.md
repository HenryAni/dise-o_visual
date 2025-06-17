# dise-o_visual

# Cambio de Tema Visual en Webmin

Este archivo explica cómo modificar el tema visual de Webmin para personalizar su apariencia.

# 1. Accede a Webmin
- Abre tu navegador.
- Escribe la dirección:  
  `https://ct-redes.digicom.com.gt`
- Inicia sesión con tus credenciales (usuario con permisos).

# 2. Ir a la configuración de Webmin
- En el menú del lado izquierdo, ve a:  
  `Webmin > Cambair hora y tema`
  `https://drive.google.com/file/d/15xgTmurKy9eygvorQnzTK2BJSXDS6esf/view?usp=sharing`

# 3. Seleccionar “Webmin Themes”
- Dentro de la configuración, haz clic en:  
  `Themes` `Temas`
  `https://drive.google.com/file/d/1AZmbd6Bp4DYf5mDpWmBFUoDjrUJEkJPl/view?usp=sharing`

# 4. Elegir un tema disponible
- Verás una lista desplegable con los temas disponibles.
- Por ejemplo, uno muy usado es el tema:  
  `Authentic Theme (default moderno)`
- Selecciona el que desees.

# 5. Aplicar el cambio
- Haz clic en:  
  `Change Theme` `Cambiar tema`
- El sistema actualizará el tema visual automáticamente.
`https://drive.google.com/file/d/13uuyg2L5Os3259jYaWNxgZsvyYInFkpv/view?usp=sharing`

# Cambiar el tema desde la terminal (opcional)

Puedes cambiar el tema desde la terminal editando el archivo de configuración:

```bash
sudo nano /etc/webmin/config
```

Busca la línea:

```bash
theme=authentic-theme
```

Y cámbiala por el nombre del nuevo tema, Guarda y sal.

Luego reinicia Webmin:

```bash
sudo systemctl restart webmin
```


## 👨‍💻 Autor

- **Nombre completo**: Henry Aníbal Veliz Ramos  
- **Correo electrónico**: hvelizr@miumg.edu.gt 
