# EspacioInvaders

Aqui está uma proposta de `README.md` estruturada e profissional para o seu GitHub, focada em destacar tanto o seu aprendizado técnico quanto o cumprimento dos requisitos acadêmicos da Estácio.

---

# Neon Invaders: Battleground

Este projeto é um jogo de sobrevivência *arcade* desenvolvido em **Linguagem C**, inspirado na estética vibrante de *Neon Battleground* e na mecânica clássica de *Space Invaders*. O objetivo é sobreviver a ondas de inimigos e obstáculos, acumulando a maior pontuação possível antes que o tempo se esgote.

Este software foi desenvolvido como parte integrante da grade curricular do curso de **Ciência da Computação da Estácio**, aplicando conceitos de Computação Gráfica, Gerenciamento de Memória e Lógica de Jogos.



## 🕹️ O Jogo
O jogador controla uma nave em um ambiente neon e deve destruir alvos em movimento. O jogo utiliza um sistema de cronômetro regressivo, exigindo agilidade para maximizar a pontuação.

### Funcionalidades Principais
* **Controle Híbrido:** Movimentação e interação via teclado e mouse.
* **Efeitos Visuais:** Uso de transparência (Alpha Blending) e brilho para simular a estética Neon.
* **Sistema de Estados:** Menu inicial, tela de pausa, vitória e derrota.
* **Persistência de Dados:** Salvamento automático de recordes e histórico de partidas em arquivo `.txt`.
* **Captura de Tela:** Funcionalidade para exportar a imagem final da partida.

## 🛠️ Bibliotecas Utilizadas
O projeto faz uso de um conjunto de bibliotecas específicas para garantir o desempenho e a compatibilidade com gráficos 2D modernos:

* **OpenGL (Open Graphics Library):** API principal utilizada para renderização de gráficos 2D, aplicação de cores e manipulação de buffers.
* **FreeGLUT:** Utilizada para a criação e gestão da janela, tratamento de eventos de entrada (teclado/mouse) e controle do loop principal do jogo.
* **stb_image / stb_image_write:** Bibliotecas *single-header* essenciais para o carregamento de texturas neon e para a funcionalidade de salvar o "print" da tela (requisito do projeto).
* **miniaudio:** Implementada para o gerenciamento de áudio, permitindo efeitos sonoros de explosões e trilha sonora de fundo sem dependências externas complexas.
* **Math.h / Stdio.h:** Bibliotecas padrão do C para cálculos de colisão (AABB/Círculo) e manipulação do arquivo de histórico.
