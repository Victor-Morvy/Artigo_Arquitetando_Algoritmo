# A importância de arquitetar uma lógica/software antes de aplica-la
### Introdução
Vejo muitos iniciantes na programação se perguntando: 
- "Como faço para criar um sistema de inventório?"
- "Como faço um sistema de quest?"
- "Como faço um sistema de ataque?"

Geralmente a resposta vem acompanha com "depende de como você quer que funcione."

Se você já possui o conhecimento básico de lógica da programação, condições, variáveis, vetores, loops e funções, você está apto a arquitetar sua lógica/software, continue, se não, "*volte 1 casa e estude lógica.*"

Neste artigo, mostrarei ao leitor os resultados e vantagens da utilização de arquitetura em sua lógica/software ao programar um sistema de inventário.

`Foi utilizado a ferramenta Construct 2, que é uma game engine 2d, baseado em html 5 e javascript, programável por blocos.`

### Objetivo
Este presente artigo tem como objetivo mostrar para o leitor por meio de resultado de experimentos a vantagem de se arquitetar uma lógica/software ao aplica-la

### Metodologia
A arquitetura de software assim como a arquitetura convencional consiste em projetar antes de aplicar, seja por esquemas gráficos, ou escrito em um papel de caderno. Você prevê futuros problemas em seu software, evitando refatoração e futuros bugs, que leva a perda de tempo e consequentemente, dinheiro.

Iniciei programando o sistema sem arquitetura alguma, no início tudo aparentava estar indo bem, comecei pela parte básica, em hardcode e decidi ir evoluindo com o tempo, mas acabei caindo no problema de não arquitetar o software. Foram acumulando os bugs e qualquer alteração eu tinha que mudar linhas e linhas, repetindo condicionais e novos bugs, foi quando depois de 2 dias (no total de umas 6, 7 horas) refatorando e refatorando, desisti da *porqueira* que havia se transformado, e resultou num total de 36 linhas (*a ferramenta construct 2 conta uma linha para cada escopo mais a esquerda na folha de eventos*).
Veja o resultado no link (Apenas link):
[CLIQUE PARA VER A IMAGEM](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/1.png?raw=true)

Depois dessa frustação, decidi aplicar a arquitetura nesse sistema, escrevi em uma folha de caderno a lógica que vai ia ser aplicada em mais ou menos 1:30h, este foi o resultado:
![alt tag](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/4.jpeg?raw=true)

Então apliquei no Construct 2, em mais ou menos 1:00h e o resultado não poderia ser melhor, além de evitar condições repetidas e acumulo de bugs, o código refatorado agora está com 12 linhas.
![alt tag](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/2.png?raw=true)
![alt tag](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/3.png?raw=true)

1/3 da quantidade de linhas e em um dia e meio a menos programando sem arquitetura de software.

### Conclusão
Como mostrado os resultado, existe uma grande vantagem em arquitetar uma lógica/software.
Foi reduzido o código em 2/3 de seu tamanho, e o tempo entre a arquitetura e a refatoração menos da metade do tempo que levei para escrever o primeiro código cheio de bugs.
Não que toda e qualquer lógica que você for montar seja necessário passar por este processo, com o tempo, ao adquirir mais experiência os algorítmos vão sair naturalmente, evitando perda de tempo desnecessário.
Mas o mesmo não se aplica a um software, que tendem ser complexos e é recomendado sempre utilizar da arquitetura de software antes de *botar a mão na massa*

Veja o resultado final:
![alt tag](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/final.png?raw=true)
![alt tag](https://github.com/Victor-Morvy/Artigo_Arquitetando_Algoritmo/blob/main/final2.png?raw=true)
