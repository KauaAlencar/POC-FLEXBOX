# POC-FLEXBOX
POC Flexbox
Este repositório contém uma prova de conceito (POC) para demonstrar as funcionalidades do Flexbox em CSS. O Flexbox é um modelo de layout unidimensional que facilita a criação de layouts flexíveis e responsivos.

Estrutura do Projeto
O projeto consiste em uma única página HTML (index.html) que inclui exemplos práticos das principais propriedades do Flexbox. O objetivo é mostrar como cada propriedade afeta o layout dos elementos dentro de um container flexível.

Conteúdo

1. justify-content
A propriedade justify-content alinha os itens ao longo do eixo principal (horizontal por padrão). Os exemplos abaixo mostram os diferentes valores que esta propriedade pode assumir:

justify-content: flex-start: Alinha os itens ao início do container.
justify-content: flex-end: Alinha os itens ao final do container.
justify-content: center: Alinha os itens ao centro do container.
justify-content: space-between: Distribui os itens com espaço igual entre eles.
justify-content: space-around: Distribui os itens com espaço igual ao redor deles.

2. align-items
A propriedade align-items alinha os itens ao longo do eixo transversal (vertical por padrão). Os exemplos incluem:

align-items: flex-start: Alinha os itens ao início do container ao longo do eixo transversal.
align-items: flex-end: Alinha os itens ao final do container ao longo do eixo transversal.
align-items: center: Alinha os itens ao centro do container ao longo do eixo transversal.
align-items: baseline: Alinha os itens ao longo da linha de base do texto.
align-items: stretch: Estica os itens para preencher o container ao longo do eixo transversal.

3. align-self
A propriedade align-self permite que um item específico se alinhe de maneira diferente dos outros itens no container. Os exemplos mostram:

align-self: flex-start: Alinha o item ao início do container ao longo do eixo transversal.
align-self: center: Alinha o item ao centro do container ao longo do eixo transversal.
align-self: flex-end: Alinha o item ao final do container ao longo do eixo transversal.

4. flex-direction
A propriedade flex-direction define a direção do eixo principal e pode ter os seguintes valores:

flex-direction: row: Alinha os itens em uma linha horizontal.
flex-direction: row-reverse: Alinha os itens em uma linha horizontal na ordem inversa.
flex-direction: column: Alinha os itens em uma coluna vertical.
flex-direction: column-reverse: Alinha os itens em uma coluna vertical na ordem inversa.

5. order
A propriedade order define a ordem dos itens no container. Os itens são ordenados de acordo com o valor numérico definido:

order: 1: O item aparece primeiro.
order: 2: O item aparece segundo.
order: 3: O item aparece por último.

## Licença

Este projeto está licenciado sob a MIT License.
