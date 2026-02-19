# Aprendizado Imersivo

### **Desenvolvedores:** André Luis Correa Cano e Bruna Carolina da Silva Feyh
### **Instituição:** Universidade Estadual do Oeste do Paraná - Unioeste - Campus Foz do Iguaçu
### **Curso:** Ciência da Computação

O trabalho propõe o uso de Realidade Virtual, com o framework **A-Frame**, para transformar o ensino de conceitos básicos em uma experiência interativa e prática. O projeto permite que estudantes explorem ambientes 3D e interajam com objetos para consolidar o conhecimento em áreas como artes e matemática.

## Jogos Disponíveis

### Mestre das Cores

Este módulo foca na teoria das cores e na lógica de mistura de pigmentos.

* **Objetivo**: O usuário recebe a missão de criar uma cor específica, como Verde, Roxo ou Laranja.
* **Interação**: É necessário selecionar dois cubos de cores primárias (Vermelho, Azul ou Amarelo) e confirmar a mistura no caldeirão virtual.
* **Feedback**: O sistema valida a combinação e fornece respostas visuais e sonoras, incluindo a emissão de bolhas coloridas em caso de acerto.

### Geometria VR

Um simulador voltado para o reconhecimento de formas geométricas no mundo real.

* **Objetivo**: Associar objetos do cotidiano, como uma bola ou um dado, às suas respectivas formas espaciais.
* **Interação**: Utilizando os controles de laser, o jogador deve apontar e clicar no sólido geométrico correto (Cubo, Esfera ou Cone) posicionado sobre a mesa virtual.
* **Recursos**: O jogo utiliza feedback para confirmar a interação correta do usuário.

## Detalhes Técnicos

* **Framework Principal**: A-Frame 1.7.0.
* **Linguagem**: JavaScript para controle de estado, lógica de pontuação e eventos de interface.
* **Ambiente**: Uso de componentes de sistema para criação de cenários florestais otimizados para VR.
* **Interface (HUD)**: Painéis suspensos que exibem o placar, instruções e mensagens de feedback em tempo real diretamente na visão do jogador.

## Instruções de Uso

1. Certifique-se de que os arquivos `index.html`, `mestre_cores.html` e `geometria_vr.html` estão no mesmo diretório, junto aos recursos de áudio e imagem.
2. Execute o arquivo `index.html` através de um navegador compatível com WebXR.
3. No menu principal, aponte o laser para o botão "JOGAR" do game desejado.
4. Para retornar ao início a qualquer momento, utilize o botão "MENU" disponível dentro da interface de cada jogo.