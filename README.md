# **POC FLEXBOX**

Este repositório é uma prova de conceito para mostrar como o Flexbox funciona em CSS. O Flexbox é uma técnica de layout unidimensional que ajuda a criar layouts flexíveis e responsivos com mais facilidade.

### **Status do Projeto**

✅ **Projeto Concluído**

### **Pré-requisitos**

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/).
Além disso, é bom ter um editor para trabalhar com o código, como [VSCode](https://code.visualstudio.com/).

### **🎲 Rodando o Projeto**

```bash
# Clone este repositório
$ git clone <https://github.com/seu-usuario/nome-do-repositorio>

# Acesse a pasta do projeto no terminal/cmd
$ cd nome-do-repositorio

# Instale as dependências (se aplicável)
$ npm install

# Abra o arquivo index.html no seu navegador
# ou utilize uma extensão como Live Server no VSCode para rodar a aplicação.
```

### **Estrutura do Projeto**
O projeto é composto por uma única página HTML (`index.html`) com exemplos práticos das principais propriedades do Flexbox. O objetivo é demonstrar como cada uma dessas propriedades pode alterar o layout dos elementos em um container flexível.

### **Conteúdo**

| Propriedade       | Descrição                                                                                                                                   |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| **justify-content** | Alinha os itens ao longo do eixo principal (normalmente horizontal).                                                                       |
| **align-items**     | Alinha os itens ao longo do eixo transversal (geralmente vertical).                                                                        |
| **align-self**      | Alinha um item específico de forma diferente dos outros itens no container.                                                                |
| **flex-direction**  | Define a direção do eixo principal, determinando como os itens são organizados dentro do container.                                        |
| **order**           | Controla a ordem dos itens no container, permitindo reordenar os itens visualmente.                                                        |
| **flex-wrap**       | Decide se os itens devem quebrar para a próxima linha quando não há espaço suficiente, ou se devem permanecer em uma única linha.          |

### **Detalhamento das Propriedades**

1. **justify-content**

   A propriedade `justify-content` alinha os itens ao longo do eixo principal (normalmente horizontal). Aqui estão alguns valores que você pode usar:

   - `flex-start`: Alinha os itens no início do container.
   - `flex-end`: Alinha os itens no final do container.
   - `center`: Alinha os itens no centro do container.
   - `space-between`: Distribui os itens com espaço igual entre eles.
   - `space-around`: Distribui os itens com espaço igual ao redor deles.

2. **align-items**

   A propriedade `align-items` alinha os itens ao longo do eixo transversal (geralmente vertical). Veja alguns exemplos:

   - `flex-start`: Alinha os itens no início do eixo transversal.
   - `flex-end`: Alinha os itens no final do eixo transversal.
   - `center`: Alinha os itens no centro do eixo transversal.
   - `baseline`: Alinha os itens com base na linha de texto.
   - `stretch`: Estica os itens para preencher o eixo transversal.

3. **align-self**

   Com `align-self`, você pode fazer um item específico se alinhar de forma diferente dos outros itens no container. Exemplos incluem:

   - `flex-start`: Alinha o item no início do eixo transversal.
   - `center`: Alinha o item no centro do eixo transversal.
   - `flex-end`: Alinha o item no final do eixo transversal.

4. **flex-direction**

   A propriedade `flex-direction` define a direção do eixo principal. Os valores são:

   - `row`: Alinha os itens em uma linha horizontal.
   - `row-reverse`: Alinha os itens em uma linha horizontal, mas na ordem inversa.
   - `column`: Alinha os itens em uma coluna vertical.
   - `column-reverse`: Alinha os itens em uma coluna vertical, na ordem inversa.

5. **order**

   A propriedade `order` controla a ordem dos itens no container. Exemplos de valores:

   - `order: 1`: O item aparece primeiro.
   - `order: 2`: O item aparece em segundo lugar.
   - `order: 3`: O item aparece por último.

6. **flex-wrap**

   A propriedade `flex-wrap` decide se os itens devem quebrar para a próxima linha quando não há espaço suficiente. Veja como usar:

   - `nowrap`: Os itens permanecem em uma única linha.
   - `wrap`: Os itens quebram para a próxima linha se necessário.
   - `wrap-reverse`: As linhas são empilhadas na direção oposta.
  
     <table>
  <tr>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/2254731?s=400&u=0ba16a79456c2f250e7579cb388fa18c5c2d7d65&v=4" width="100px;" alt=""/><br /><sub><b>Diego Fernandes</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">👨‍🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/4669899?s=460&u=806503605676192b5d0c363e4490e13d8127ed64&v=4" width="100px;" alt=""/><br /><sub><b>Cleiton Souza</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">👨‍🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/861751?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Robson Marques</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">👨‍🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/16831337?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Claudio Orlandi</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">🚀</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars0.githubusercontent.com/u/39345247?s=460&u=cdff2624a327a43e2765112a54e966a06eac6d79&v=4" width="100px;" alt=""/><br /><sub><b>Joseph Oliveira</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars0.githubusercontent.com/u/10366880?s=460&u=59e93e1752e9d2ece4b7d8e129d60caba9c94207&v=4" width="100px;" alt=""/><br /><sub><b>Guilherme Rodz</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/37725197?s=460&u=446439436524c37f66e41f35b607dbb70358d5e4&v=4" width="100px;" alt=""/><br /><sub><b>Vinícios Fraga</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">🚀</a></td>
    <td align="center"><a href="https://rocketseat.com.br"><img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/26551306?s=460&u=18446655ccae6c2a29eb177a104ecf32f029aa3a&v=4" width="100px;" alt=""/><br /><sub><b>Hugo Duarte</b></sub></a><br /><a href="https://rocketseat.com.br/" title="Rocketseat">🚀</a>  <a href="https://blog.rocketseat.com.br/" title="Blog">🌐</a></td>
  </tr>
</table>

### **📝 Licença**

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.
