## Visualizador de Árvore AVL
Este projeto é uma ferramenta interativa e educativa para a visualização de uma Árvore AVL. O usuário pode inserir e remover valores, observando em tempo real como a árvore se reestrutura através de rotações para manter sua altura otimizada.

## Funcionalidades
• **Inserção Interativa**: Adicione novos nós e veja o processo de balanceamento automático. <br>
• **Remoção de Nós**: Remova qualquer nó da árvore, com o sistema tratando automaticamente os casos de nós folha, com um filho ou com dois filhos. <br>
• **Balanceamento Automático**: Implementação de rotações simples e duplas (esquerda e direita) baseadas no fator de balanceamento ($bal$). <br>
• **Visualização Gráfica**: Representação visual dinâmica utilizando SVG, com cores que indicam o estado de cada nó: <br>
> 🔵 Azul: Nó balanceado ($bal = 0$) <br>
🟢 Verde: Desbalanceado à esquerda ($bal = -1$) <br>
> 🔴 Vermelho: Desbalanceado à direita ($bal = 1$) <br>

• **Percursos da Árvore**: Exibição em tempo real dos percursos: <br>
> Pré-ordem <br>
 Ordem Simétrica (In-order) <br>
 > Pós-ordem <br>
 
• **Árvore de Exemplo**: Botão para gerar rapidamente uma árvore populada para testes. <br>

## Tecnologias Utilizadas
• **HTML5 & CSS3**: Estrutura e estilização <br>
• **Tailwind CSS**: Framework utilitário para um design moderno e responsivo <br>
• **JavaScript (ES6+)**: Lógica da estrutura de dados, algoritmos de rotação e manipulação do DOM <br>
• **SVG (Scalable Vector Graphics)**: Para renderizar a árvore de forma nítida em qualquer resolução <br>

## Como executar
1.Faça o download do arquivo ```index.html``` <br>
2.Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge, etc.) <br>
3.Pronto! Já pode começar a interagir com a árvore <br>

### Autora
Desenvolvido por Bianca Barros <br>
Data: 22/08/2025
