# 🌊 MOODwave - Generador de Playlists según tu Estado de Ánimo (IA)

**MOODwave** es un proyecto ganador de hackathon que combina **inteligencia artificial** y **música** para mejorar tu bienestar emocional.  
A través de texto o voz, la app detecta tu estado de ánimo usando la **API de OpenAI**, interpreta tu emoción y genera una **playlist personalizada en Spotify** que refleja cómo te sientes.

---

## 🚀 Funcionalidades
- 🎙️ **Entrada por voz o texto** para indicar tu mood.
- 🤖 **Detección de emociones con IA** (OpenAI API).
- 🎧 **Generación automática de playlist en Spotify** según tu emoción (Spotify API).
- 🌐 **Interfaz web responsiva** con HTML, Tailwind CSS y JavaScript.
- 🐍 **Backend en Python** para la lógica y manejo de APIs.
- 📲 **Generación de código QR** para compartir tu playlist.

---

## 🛠️ Tecnologías usadas
**Frontend:** HTML5, Tailwind CSS, JavaScript  
**Backend:** Python (Flask)  
**APIs:**
- OpenAI API (análisis de emociones en texto/voz)
- Spotify API (creación de playlists)
  
**Otros:** GitHub, Replit (testing)

---

## 📦 Instalación
```bash
# 1. Clonar el repositorio
git clone https://github.com/351jimenavel/Hackathon-_404_NF.git
cd Hackathon-_404_NF

# 2. Instalar dependencias
pip install -r requirements.txt

# 3. Configuración de Variables de Entorno
# Crea un archivo `.env` en la raíz del proyecto con las siguientes variables:

# (a) Clave de API de OpenAI (para análisis de emociones y generación de texto)
OPENAI_API_KEY=tu_api_key

# (b) Credenciales de Spotify (desde el Dashboard de Spotify Developers)
SPOTIFY_CLIENT_ID=tu_client_id_aqui
SPOTIFY_CLIENT_SECRET=tu_client_secret_aqui

# (c) URL de redirección de Spotify
# Para entorno local, usar:
SPOTIFY_REDIRECT_URI=http://127.0.0.1:8000/callback

# (d) Define los permisos que la aplicación solicitará a Spotify
SCOPE=playlist-modify-public

# Nota: Este valor debe coincidir EXACTAMENTE con el configurado en el Dashboard de Spotify Developers.

# 4. Ejecutar la aplicación
python app1.py
```
---

## 🏆 Logro en Hackathon
🥇 Ganador de hackathon en Penguin Academy, Paraguay, demostrando análisis de emociones en tiempo real y recomendaciones musicales usando herramientas de IA modernas y APIs públicas.

Desarrollado por [Alan Riquelme](https://github.com/alanriquelmee), [Jimena Velázquez](https://github.com/351jimenavel), [Maximiliano Orue](https://github.com/MaxiOru), [Efraín Ortiz](https://github.com/Efraor), [Melizza Benitez](https://github.com/jazminbenitez), Camila Torres como parte de un desafío de hackathon.
