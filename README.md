# San Francisco 10 - Guía QR para Alicante 

Sistema de guías PDF accesibles mediante código QR para huéspedes.

## 📁 Estructura del proyecto

```
SF10-QR-Menu/
├── index.html          ← Página principal (selector de idioma)
├── pdfs/
│   ├── Guia_SF10ES.pdf ← Guía en español (DEBES COPIAR AQUÍ)
│   └── Guide_SF10EN.pdf ← Guía en inglés (DEBES COPIAR AQUÍ)
└── README.md
```

## 🚀 Pasos para publicar GRATIS

### Opción 1: Netlify (Recomendado - Más fácil)

1. Ve a [netlify.com](https://www.netlify.com/) y crea una cuenta gratuita
2. En el dashboard, arrastra la carpeta `SF10-QR-Menu` completa
3. ¡Listo! Te dará una URL como: `https://tu-sitio.netlify.app`
4. Puedes personalizar el nombre del sitio en Site settings

**URLs que tendrás:**
- Página principal: `https://tu-sitio.netlify.app`
- PDF Español directo: `https://tu-sitio.netlify.app/pdfs/Guia_SF10ES.pdf`
- PDF Inglés directo: `https://tu-sitio.netlify.app/pdfs/Guide_SF10EN.pdf`

### Opción 2: GitHub Pages (Gratis)

1. Crea una cuenta en [github.com](https://github.com)
2. Crea un nuevo repositorio llamado `sf10-guia`
3. Sube todos los archivos de esta carpeta
4. Ve a Settings → Pages → Source: "main" branch
5. Tu sitio estará en: `https://tu-usuario.github.io/sf10-guia`

---

## 📱 Generar Código QR

Una vez tengas la URL, genera el código QR gratis en:
- [qr-code-generator.com](https://www.qr-code-generator.com/)
- [qrcode-monkey.com](https://www.qrcode-monkey.com/)

**Recomendación:** Usa la URL de la página principal para que el cliente elija idioma:
```
https://tu-sitio.netlify.app
```

O si quieres 2 QR separados (uno por idioma):
```
https://tu-sitio.netlify.app/pdfs/Guia_SF10ES.pdf
https://tu-sitio.netlify.app/pdfs/Guide_SF10EN.pdf
```

---

## ⚠️ IMPORTANTE: No olvides copiar tus PDFs

Antes de subir, copia tus archivos PDF a la carpeta `pdfs/`:
- `Guia_SF10ES.pdf`
- `Guide_SF10EN.pdf`

---

## 🎨 Personalización

Si quieres cambiar colores o textos, edita el archivo `index.html`.

Colores actuales (estilo mediterráneo):
- Terracota: #C84B31
- Azul mediterráneo: #1A659E
- Azul profundo: #0D3B66
- Arena: #F5E6D3
- Dorado: #D4A853

