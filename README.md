from pathlib import Path

# Contenido del archivo README.md personalizado
readme_content = """
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&center=true&vCenter=true&multiline=true&width=800&height=100&lines=Hola%2C+soy+David+Lopez;Estudiante+de+Ingenier%C3%ADa+Electr%C3%B3nica+%7C+USTA+-+Bogot%C3%A1" alt="Typing SVG" />
</h1>

<div align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="250"/>
</div>

---

## 🎓 Formación Académica

- 🏫 **Universidad Santo Tomás**
  - 🧑‍🎓 *Estudiante de Ingeniería Electrónica*
  - 📍 Bogotá, Colombia
  - 🗓️ 2021 – Presente
  - 🔬 Enfocado en: Automatización, Electrónica de Potencia, Control, Sistemas embebidos, Robótica.

---

## 🧠 Habilidades Técnicas (Hard Skills)

- Lenguajes de programación: **C, C++, C#, Assembler (8051)**
- Microcontroladores y DSPs: **Arduino, ESP32, STM32, LAUNCHXL-F28379D**
- Diseño electrónico con: **Proteus, Multisim, KiCad**
- Programación orientada a objetos (**POO**) en C#
- Control de motores: PWM, Puentes H, controladores PID
- Electrónica de potencia aplicada a sistemas de iluminación
- Protocolos de comunicación: UART, SPI, I2C
- Manejo básico de sistemas en tiempo real

---

## 🌟 Habilidades Blandas (Soft Skills)

- 🤝 Trabajo en equipo interdisciplinario
- 🧠 Pensamiento crítico y lógico
- 🎯 Enfoque en solución de problemas reales
- 💬 Comunicación clara y asertiva
- 🔍 Curiosidad técnica constante

---

## ⚙️ Herramientas y Tecnologías

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,cs,arduino,vscode,git,github,linux,matlab" />
</p>

---

## 🧪 Proyectos Destacados

| Proyecto | Descripción | Tecnologías |
|----------|-------------|-------------|
| 🚗 **Carro seguidor de línea (análogico y digital)** | Implementación de sensores IR y control de velocidad | Comparadores, C, L298N |
| 🕷️ **Araña robótica** | Controlada desde el PC mediante comunicación serial | C++, interfaz con Python |
| ⚙️ **Sistema de control de motores** | Implementación de PID, control PWM, puentes H | DSP F28379D, C |
| 💡 **Driver LED con Electrónica de Potencia** | Control de encendido/apagado y modulación de potencia | Transistores, PWM, C, Proteus |

---

## 🌐 Idiomas

| Idioma    | Nivel | Descripción breve |
|-----------|-------|--------------------|
| 🇪🇸 Español  | Nativo | Lengua materna. Excelente comprensión oral y escrita. |
| 🇺🇸 Inglés   | B2 | Lectura fluida de documentación técnica, redacción y conversación. |
| 🇩🇪 Alemán   | A2 | Conocimientos básicos: expresiones comunes y gramática inicial. |

---

## 📊 Estadísticas de GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=LopezzzDavid&show_icons=true&theme=tokyonight" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LopezzzDavid&layout=compact&theme=tokyonight" />

</div>

---

## 📬 Contacto

<p align="center">
  <a href="mailto:lopezzzdavid@example.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://linkedin.com/in/lopezzzdavid"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

---

<div align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="80"/>
  <em>Gracias por visitar mi perfil. ¡Siempre abierto a colaborar y aprender más! 🚀</em>
</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=LopezzzDavid&label=Visitas&color=blue&style=flat" alt="LopezzzDavid" />
</p>
"""

# Guardar el archivo como README.md
output_path = Path("/mnt/data/README.md")
output_path.write_text(readme_content.strip(), encoding="utf-8")

output_path

