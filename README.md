# PDF → Infografía visual

Aplicación web que convierte documentos (PDF, Word, texto o URLs) en infografías tipo póster usando IA.

## Características

- 📄 Soporta PDF, DOCX, TXT, MD, HTML y URLs (vía Jina Reader)
- 🌍 10 idiomas de salida (español, inglés, catalán, gallego, euskara, portugués, francés, italiano, alemán, neerlandés)
- 📐 3 formatos: vertical (A4), horizontal (16:9), cuadrado (1:1)
- 🎨 5 temas visuales: verde, azul, morado, naranja, oscuro
- 📊 3 niveles de detalle: medio, detallado, exhaustivo
- 🤖 Multi-proveedor: Gemini, Groq, OpenRouter, DeepSeek, OpenAI
- 🌓 Modo claro/oscuro de la interfaz
- 💾 Exporta como PNG o HTML
- 🔒 Todo se ejecuta en el navegador, las API keys no salen de tu equipo

## Cómo usarlo

1. Abre la app (o clona el repo y abre `index.html`)
2. Pega tu API key del proveedor elegido
3. Sube un archivo o pega una URL
4. Configura formato, tema, idioma y nivel de detalle
5. Pulsa "Generar infografía"

## Proveedores soportados

| Proveedor | Key gratis | PDF nativo |
|---|---|---|
| Google Gemini | ✅ [aistudio.google.com/apikey](https://aistudio.google.com/apikey) | ✅ |
| Groq | ✅ [console.groq.com/keys](https://console.groq.com/keys) | ❌ (extrae texto) |
| OpenRouter | ✅ [openrouter.ai/keys](https://openrouter.ai/keys) | ❌ |
| DeepSeek | ❌ | ❌ |
| OpenAI | ❌ | ❌ |

## Despliegue

Súbelo a Netlify, Vercel o Cloudflare Pages. Es un único HTML estático.

## Licencia

MIT
