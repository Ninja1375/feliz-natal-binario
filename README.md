# Feliz Natal Binário 🎄💻

"Feliz Natal Binário" é um projeto criativo e interativo que traz uma fusão de animações inspiradas no filme *Matrix* com uma mensagem especial de Natal e um toque de programação. A proposta é proporcionar uma experiência única e visualmente envolvente com animações dinâmicas e um toque de magia para saudar o Natal e o novo ano.

**Veja o projeto ao vivo:**

**[Feliz Natal Binário](https://ninja1375.github.io/feliz-natal-binario/)**

![Feliz Natal Binário ](https://github.com/user-attachments/assets/68262c79-66f7-4ad8-830a-90fe2afc861d)


## 🎯 Objetivo do Projeto

Este projeto foi criado para:

- Mostrar como a animação pode ser aplicada de forma criativa utilizando JavaScript, CSS e HTML.
- Usar a estética visual inspirada no código binário e a famosa "Matrix" para criar uma animação que celebra o Natal de uma maneira única.
- Adicionar um toque interativo com mensagens personalizadas que aparecem e desaparecem em um estilo de digitação dinâmica.

A proposta de "Feliz Natal Binário" é envolver o usuário com uma atmosfera festiva e ao mesmo tempo destacar a beleza do código e da programação, como uma forma de desejar boas festas.

## 🛠️ Tecnologias Utilizadas

<a href="https://programartudo.blogspot.com/2024/11/html-tudo-o-que-precisa-para-comecar.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/></a> <a href="https://programartudo.blogspot.com/2024/11/css-como-dar-estilo-ao-teu-website.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/></a> <a href="https://programartudo.blogspot.com/2024/11/javascript-linguagem-dinamica-da-web.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40"/></a> <a href="https://getuikit.com/" target="_blank"> <img loading="lazy" src="https://raw.githubusercontent.com/uikit/uikit/772522a0afc623afe363b139954cb2d9f4c4f017/src/images/icons/uikit.svg" width="40" height="40"/></a> <a href="https://jquery.com/" target="_blank"> <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" width="40" height="40"/></a>

Este projeto utiliza as seguintes tecnologias:

- **HTML**: Estrutura do projeto, definindo a marcação semântica do conteúdo.
- **CSS**: Estilização das animações, efeitos de transição e layout responsivo.
- **JavaScript**: Lógica de animação, manipulação da DOM e efeitos interativos.
- **UIkit**: Framework CSS para facilitar o design responsivo e componentes interativos.
- **jQuery**: Manipulação da DOM e auxílio na criação da animação de digitação.

## 📂 Estrutura de Arquivos

O projeto é composto pelos seguintes arquivos principais:

- **index.html**: Contém a estrutura HTML do projeto, onde o layout e a disposição dos elementos são definidos.
- **style.css**: A folha de estilo CSS que define as animações e o design visual, incluindo o estilo da matriz e dos textos.
- **script.js**: O arquivo JavaScript responsável por criar a animação da matriz, o efeito de digitação e o processo de deterioração da matriz.

## 🚀 Funcionalidades

Este projeto contém várias funcionalidades para criar uma experiência única e interativa. As principais são:

1. **Animação de Matriz (Estilo Matrix)**:
   - A animação exibe uma matriz de caracteres binários (0s e 1s) que se movem pela tela, com pontos brilhantes que simulam um efeito de brilho nas posições aleatórias.
   - O código utiliza caracteres especiais, como "*", para representar pontos de brilho e "O" para criar o efeito de "deterioração" da matriz.

2. **Efeitos de Digitação Dinâmica**:
   - Duas mensagens são exibidas na tela com um efeito de digitação:
     - **"Feliz Natal"** (primeira mensagem)
     - **"E um 2025 repleto de (códigos)coisas boas"** (segunda mensagem)
   - As mensagens são digitadas uma letra por vez, com uma animação de "apagamento" antes de mostrar a próxima mensagem.

3. **Efeito de Dissolução**:
   - Após um certo tempo, a matriz começa a "desaparecer", criando um efeito de deterioração em que as posições com "O" se espalham horizontal e verticalmente, criando uma animação de destruição.
   - O efeito de dissolução começa após um determinado tempo e tem uma velocidade ajustável, permitindo maior controle sobre o comportamento da animação.

## 🌟 Como Executar o Projeto

Para rodar este projeto em sua máquina local, siga os seguintes passos:

1. **Faça o download ou clone o repositório**:
   ```bash
   git clone https://github.com/Ninja1375/feliz-natal-binario.git

2. **Abra o arquivo `index.html`**:
   - O projeto não depende de servidores backend, então você pode simplesmente abrir o arquivo `index.html` em qualquer navegador moderno.
   - Ao abrir o arquivo, as animações e efeitos começarão automaticamente.

3. **Requisitos**:
   - Este projeto utiliza bibliotecas externas através de CDNs. Certifique-se de estar conectado à internet para carregar as bibliotecas necessárias, como **UIkit** e **jQuery**.

## Configurações Personalizáveis

Você pode personalizar o comportamento da animação ajustando os seguintes parâmetros no arquivo `script.js`:

- **frameTimer**: 
  - Controla o intervalo entre os quadros de animação. O valor padrão é `60ms`, mas você pode ajustar esse valor para tornar a animação mais rápida ou mais lenta.
  
- **frameLifespan**:
  - Define o tempo de vida de cada quadro da matriz em milissegundos. Um valor maior faz com que cada quadro permaneça visível por mais tempo antes de desaparecer.

- **sparkleNess**:
  - Ajusta a intensidade do brilho da matriz. O valor vai de `0` a `1`. Um valor próximo de `1` aumenta o brilho, enquanto um valor próximo de `0` reduz o brilho.

- **decayStart**:
  - Controla o tempo, em milissegundos, após o qual a animação de dissolução começa. O valor padrão é `2000ms`, ou seja, a dissolução começa após 2 segundos.

- **decaySpeed**:
  - Define a velocidade da dissolução dos quadros. Quanto maior o valor, mais suave será o efeito de deterioração.

- **horizontalSpeed** e **verticalSpeed**:
  - Ajustam a propagação da destruição horizontal e vertical da matriz. Valores entre `0` e `1` permitem que você controle o quão rápido a matriz se deteriora na horizontal e vertical.

## Apoie-me:

<a href="https://buymeacoffee.com/antonio13" target="_blank"><img loading="lazy" src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=seu_nome_de_usuario&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" width="130" height="30"></a>

<a href="https://www.paypal.com/donate/?hosted_button_id=DN574F28FYUNG" target="_blank"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" width="130" height="30"></a>

<a href="https://github.com/sponsors/Ninja1375" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Sponsor-ea4aaa?style=for-the-badge&logo=github&logoColor=white" width="130" height="30"></a>

**Boas festas e bons códigos! 🎅🎄**
