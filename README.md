# Jogo do Número Secreto
Este é um jogo simples onde o objetivo é adivinhar um número secreto gerado aleatoriamente. O jogador utiliza comandos de voz para dar seus palpites, e o jogo fornece dicas se o número secreto é maior ou menor que o palpite fornecido.


## Índice
- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Como Jogar](#como-jogar)
- [Instalação](#instalação)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)


Descrição do Projeto
O jogo gera um número secreto aleatório entre 1 e 100. O jogador tenta adivinhar o número falando seus palpites em voz alta. O jogo usa a API de reconhecimento de voz do navegador para capturar o palpite do jogador. A cada tentativa, o jogo indica se o número secreto é maior ou menor que o palpite dado. Quando o número é acertado, o jogo exibe uma mensagem de vitória e oferece a opção de jogar novamente.


## Funcionalidades
Geração de um número secreto aleatório.
Captura de comandos de voz para receber o palpite do jogador.
Validação dos palpites, garantindo que estão dentro do intervalo permitido.
Indicação visual e textual se o palpite é maior ou menor que o número secreto.
Opção de jogar novamente após acertar o número secreto.


## Como Jogar
Abra o arquivo index.html em um navegador que suporte a API de reconhecimento de voz.
O jogo exibirá o intervalo de números possíveis e aguardará seu palpite.
Diga um número dentro do intervalo permitido.
O jogo indicará se o número secreto é maior ou menor que seu palpite.
Continue tentando até acertar o número secreto.
Ao acertar, clique em "Jogar novamente" para reiniciar o jogo.


## Instalação
Clone o repositório para sua máquina local.
Certifique-se de que o arquivo index.html e os arquivos JavaScript (sortearNumero.js, reconhecimentoDeVoz.js, validacao.js) estão na mesma pasta ou em seus respectivos diretórios.
Abra o arquivo index.html em um navegador.


## Estrutura do Projeto
- ├── index.html             # Página principal do jogo
- ├── style.css              # Estilos para a página
- └── app/
    - ├── sortearNumero.js   # Lógica para gerar o número secreto e exibir os valores mínimos e máximos
    - ├── reconhecimentoDeVoz.js # Lógica para capturar e processar o comando de voz do usuário
    - └── validacao.js       # Lógica para validar o palpite do usuário e interagir com a interface do jogo


## Tecnologias Utilizadas
HTML5: Estruturação da página.
CSS3: Estilização da interface.
JavaScript: Lógica do jogo e manipulação do DOM.
API de Reconhecimento de Voz: Para capturar e processar comandos de voz do usuário.
 
