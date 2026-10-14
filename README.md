<h1 align="center">Olá! Eu sou Rin&lt;code&gt; 👋</h1>

<p align="center">
  Aprendendo <b>IoT</b>, <b>sistemas embarcados</b> e <b>desenvolvimento web</b> construindo projetos de verdade.<br>
  🎯 <b>Aberto a oportunidades de estágio.</b>
</p>

---

## 🤖 Projeto em destaque: Bandejito 1.0

**Robô garçom em miniatura com ESP32-CAM**: vídeo ao vivo e controle pelo navegador, simulador completo no PC e um modo autônomo que segue uma fita no chão até a mesa certa, dá meia-volta e volta para o balcão.

<p align="center">
  <img src="imagens/modelo_3d.gif" alt="Modelo 3D do Bandejito girando, com a carcaça e depois por dentro" height="300">
  <img src="imagens/simulador_autonomo.gif" alt="Simulador do Bandejito: o robô leva o pedido até a mesa 2, dá meia-volta e volta para o balcão" height="300">
</p>

- 📡 O robô cria a própria rede Wi-Fi e serve um painel web com vídeo MJPEG
- 🛑 Parada de segurança automática se a conexão cair
- 🖥️ Simulador em Node.js com a mesma API do firmware, para testar sem hardware
- 🧭 Seguidor de linha com controle PD, meia-volta no lugar, fila de pedidos e freio diante de obstáculos (no simulador)
- 🖨️ Carcaça 3D paramétrica gerada por código (CadQuery/OpenSCAD)

| Painel de controle (vídeo ao vivo + direção) | Página de pedidos (modo autônomo) |
|---|---|
| ![Painel de controle do robô](imagens/painel.png) | ![Página de pedidos](imagens/pedidos.png) |

👉 **[Ver o repositório](https://github.com/rincode-dev/robo-garcom-iot)** · Status: software pronto e testado no simulador, montagem do robô físico em andamento.

---

## 🛠️ Tecnologias que usei

![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?logo=arduino&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?logo=platformio&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion%20360-FF6B00?logo=autodesk&logoColor=white)
