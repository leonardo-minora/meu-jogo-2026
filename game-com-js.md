# Para quem deseja programar com Javascript

Orientação by [Google gemini](https://gemini.google.com/)

---

### **1. Jogos 2D (Renderização via Canvas)**

* **Phaser.js** (A mais popular para 2D)
* **Indicado para:** Jogos 2D completos de qualquer tipo (plataforma, RPG, arcade).
* **Destaques:** Suporta física (Arcade e Matter.js), gerenciamento de sprites, suporte a som, mapas de tiles (Tiled) e entrada de teclado/touch/gamepad.
* **Exemplo de uso:** Jogos para navegadores e dispositivos móveis via WebView.


* **PixiJS** (Motor de Renderização 2D)
* **Indicado para:** Jogos ou aplicações que precisam de renderização 2D extremamente rápida e uso intensivo de WebGL.
* **Destaques:** Não é uma engine de jogo completa (não possui sistema de física embutido), mas é o renderizador 2D mais rápido do ecossistema JS. Pode ser combinada com bibliotecas de física como Matter.js.


* **Kontra.js** (Leve e rápida)
* **Indicado para:** Jogos leves, projetos de game jams (como a *JS13kGames*) ou aprendizado.
* **Destaques:** Ocupa pouquíssimo espaço (menos de 10 KB), cobrindo o básico: loop de jogo, sprites, entradas e áudio.



---

### **2. Jogos 3D (Renderização via WebGL / WebGPU)**

* **Three.js** (A biblioteca 3D padrão)
* **Indicado para:** Visualizações 3D, experiências interativas e jogos 3D simplificados.
* **Destaques:** Facilita a criação de cenários 3D, iluminação, sombras e modelos (glTF/OBJ). Para física 3D, costuma ser combinada com motores como **Cannon.es** ou **Rapier**.


* **Babylon.js** (Engine 3D completa)
* **Indicado para:** Jogos 3D mais robustos e complexos diretamente no navegador.
* **Destaques:** Desenvolvida e mantida pela Microsoft. Possui motor de física integrado, suporte a VR/AR (WebXR), editores visuais e suporte total a WebGL/WebGPU.



---

### **3. Motores de Física (Para usar com PixiJS, Three.js ou HTML/Canvas)**

* **Matter.js:** Física 2D (corpos rígidos, colisões, gravidade).
* **Cannon.es:** Física 3D leve para ser combinada com Three.js.
* **Rapier:** Motor de física 2D e 3D extremamente rápido, escrito em Rust e compilado para WebAssembly.

---

### **4. Jogos baseados exclusivamente em DOM (HTML/CSS + JS)**

Para jogos baseados em texto, cartas, quebra-cabeças ou RPGs táticos sem renderização intensiva em Canvas, pode-se usar bibliotecas/frameworks de interface:

* **Kaboom.js:** Ótima para iniciantes criarem jogos retro 2D rapidamente.
* **React / Vue / Svelte:** Embora não sejam motores de jogos, são amplamente utilizados para criar jogos de cartas (estilo *Hearthstone*), jogos de estratégia em turnos ou jogos baseados em menus e CSS.
