<h1 align="center">Olá! Eu sou Rin&lt;code&gt; 👋</h1>

<p align="center">
  Aprendendo <b>IoT</b>, <b>sistemas embarcados</b> e <b>desenvolvimento web</b> construindo projetos de verdade.<br>
  🎯 <b>Aberto a oportunidades de estágio.</b>
</p>

---

## 🤖 Projeto em destaque: Bandejito 1.0

**Robô garçom em miniatura com ESP32-CAM**: vídeo ao vivo e controle pelo navegador, simulador completo no PC e um modo autônomo que segue uma fita no chão até a mesa certa, vira de frente para ela, avisa por voz e volta para o balcão quando o cliente aperta o botão verde.

<p align="center">
  <img src="imagens/bandejito_esqueleto_3d.gif" alt="Modelo 3D do Bandejito: volta completa, portinhas abrindo e fechando, montagem peça por peça, eletrônica e fios por dentro e o chassi" height="300">
  <img src="imagens/bandejito_maquete_3d.gif" alt="Animação 3D na maquete: o Bandejito leva o pedido à Mesa 2, espera uma pessoa sair do caminho, gira 90° até ficar de frente para a mesa, o cliente pega o copo e aperta o botão verde, e ele volta ao balcão" height="300">
</p>

- 📡 O robô cria a própria rede Wi-Fi e serve um painel web com vídeo MJPEG
- 🛑 Parada de segurança automática se a conexão cair e partida suave (o robô alto não "empina")
- 🖥️ Simulador em Node.js com a mesma API do firmware, para testar sem hardware
- 🧭 Seguidor de linha com controle PD, giro de 90° até a mesa, mensagem de voz, botão verde, fila de pedidos e freio diante de obstáculos (no simulador)
- 🖨️ Carcaça 3D paramétrica gerada por código (CadQuery/OpenSCAD), com bandejas, portinhas de encaixe e pé antitombo, validada no modelo (colisões e centro de massa)

| Painel de controle (vídeo ao vivo + direção) | Página de pedidos (modo autônomo) |
|---|---|
| ![Painel de controle do robô](imagens/painel.png) | ![Página de pedidos](imagens/pedidos.png) |

👉 **[Ver o repositório](https://github.com/rincode-dev/robo-garcom-iot)** · Status: software pronto e testado no simulador; principais peças compradas, montagem do robô físico em seguida.

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
