# Projeto Pixels Art

Projeto realizado na Trybe como encerramento do Bloco 5 - JavaScript: DOM, Eventos e Web Storage, onde utilizamos HTML, CSS e JavaScript.

## Objetivo
 
Desenvolver um editor de arte onde o usuário tenha uma paleta de cores e consiga desenhar em quadro de pixels. Utilizar conceitos de manipulação do Dom e JavaScript.

## Requisitos

#### 1 - Adicione à página o título "Paleta de Cores".

O título deverá ficar dentro de uma tag `h1` com o `id` denominado `title`. O texto do título deve ser **exatamente** "Paleta de Cores".

#### 2 - Adicione à página uma paleta contendo quatro cores distintas.

A paleta de cores deve ser um elemento com `id` denominado `color-palette`, ao passo que cada cor individual contida na paleta de cores deve possuir a `classe` `color`. A cor de fundo de cada elemento da paleta deverá ser a cor que o elemento representa. **A única cor não permitida na paleta é a cor branca.**. Cada elemento da paleta de cores deverá ter uma borda preta, sólida e com 1 pixel de largura;

A paleta de cores deverá listar todas as cores disponíveis para utilização lado a lado, e deverá ser posicionada abaixo do título "Paleta de Cores", a mesma não deve conter cores repetidas.

#### 3 - Adicione a cor **preta** como a primeira cor da paleta de cores.

A primeira cor da paleta deve ser preta e as demais cores podem ser escolhidas livremente.

#### 4 - Adicione à página um quadro de pixels, com 25 pixels.

O quadro de "pixels" deve ter 5 elementos de largura e 5 elementos de comprimento, deve possuir o `id` denominado `pixel-board`, ao passo que cada "pixel" individual dentro do quadro deve possuir a `classe` denominada `pixel`. A cor inicial dos "pixels" dentro do quadro, ao abrir a página, deve ser branca. O quadro de "pixels" deve aparecer abaixo da paleta de cores.

#### 5 - Faça com que cada elemento do quadro de pixels possua 40 pixels de largura, 40 pixels de altura e seja delimitado por uma borda preta de 1 pixel.

O quadro de pixels tem altura e comprimento de 5 elementos, 40 pixels deve ser o tamanho total do elemento, incluindo seu conteúdo e excluindo a borda preta, que deve ser criada à parte.

#### 6 - Defina a cor preta como cor inicial. Ao carregar a página, a cor preta já deve estar selecionada para pintar os pixels

O elemento da cor preta deve possuir, inicialmente, a `classe` `selected`. Note que o elemento que deverá receber a classe `selected` deve ser um dos elementos que possuem a classe `color`, como especificado no **requisito 2**.

#### 7 - Clicar em uma das cores da paleta faz com que ela seja selecionada e utilizada para preencher os pixels no quadro.

A `classe` `selected` deve ser adicionada à cor selecionada na paleta, ao mesmo tempo em que é removida da cor anteriormente selecionada. Somente uma das cores da paleta deve ter a `classe` `selected` de cada vez. Note que os elementos que deverão receber a classe `selected` devem ser os mesmos elementos que possuem a classe `color`, como especificado no **requisito 2**.

#### 8 - Clicar em um pixel dentro do quadro após selecionar uma cor na paleta faz com que o pixel seja preenchido com a cor selecionada.

Ao carregar a página deve ser possível pintar os pixels de preto. Após selecionar uma outra cor na paleta, é possível pintar os pixels com essa cor, somente o pixel que foi clicado foi preenchido com a cor selecionada, sem influenciar na cor dos demais pixels.

#### 9 - Crie um botão que, ao ser clicado, limpa o quadro preenchendo a cor de todos seus pixels com branco.

O botão tem o `id` denominado `clear-board` e deve estar posicionado entre a paleta de cores e o quadro de pixels. O texto do botão deve ser \'Limpar\' e ao clicar no botão, o quadro de pixels é totalmente preenchido de branco.

#### 10 - Faça o quadro de pixels ter seu tamanho definido pela pessoa usuária.

Crie um input e um botão que permitam definir um quadro de pixels com tamanho entre 5 e 50. Ao clicar no botão, deve ser gerado um quadro de **N** pixels de largura e **N** pixels de altura, onde **N** é o número inserido no input. O input deve ter o `id` denominado `board-size` e o botão deve ter o `id` denominado `generate-board` e só deve aceitar número maiores que zero. Essa restrição **deve** ser feita usando os atributos do elemento `input`. O botão deve conter o texto "VQV". O input deve estar posicionado entre a paleta de cores e o quadro de pixels. O botão deve estar posicionado ao lado do input;

Se nenhum valor for colocado no input ao clicar no botão, mostre um `alert` com o texto: "Board inválido!";

O novo quadro deve ter todos os pixels preenchidos com a cor branca.

#### 11 - Limite o tamanho mínimo e máximo do board.

Caso o valor digitado no input `board-size` fuja do intervalo de 5 a 50, faça:

  - Valor menor que 5, considerar 5 como padrão;

  - Valor maior que 50, considerar 50 como padrão.

#### 12 - Faça com que as cores da paleta sejam geradas aleatoriamente ao carregar a página.

A cor preta ainda precisa estar presente e deve ser a primeira na sua paleta de cores.

--- 

## Projeto Aprovado!

![Captura de tela de 2022-05-01 15-22-51](https://user-images.githubusercontent.com/98956659/166150234-94c3b821-692a-47b4-869e-94b44d57c3f0.png)

#### [Experimente](https://larissaperinoto.github.io/project-pixels-art/) a aplicação
![Captura de tela de 2022-05-01 15-25-35](https://user-images.githubusercontent.com/98956659/166150368-08de33a7-bfa2-4638-a4fb-c7caa542e1a0.png)
