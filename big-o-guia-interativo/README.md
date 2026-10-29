# Big O: guia interativo

Material de apoio do trabalho **“Big O e Complexidade de Algoritmos”**, do curso de Ciência da Computação.

Um site de uma página só que explica a notação Big O sem complicação: com analogias do dia a dia, exemplos em Python, demonstrações para mexer e um desafio no final. O trabalho escrito, no padrão ABNT, está em [`docs/`](docs/Big_O_e_Complexidade_de_Algoritmos.pdf).

## O que tem no site

- **Resumo em um minuto**: o que é Big O, por que importa e como simplificar.
- **Seis módulos**, um para cada classe: O(1), O(log n), O(n), O(n log n), O(n²) e O(2ⁿ). Cada módulo tem analogia, sinais para reconhecer a classe no código, exemplo comentado, uma demonstração interativa e um teste rápido.
- **Transições em forma de gráfico**: ao abrir um módulo, a curva dele é desenhada no plano cartesiano e a página se abre a partir da ponta da curva.
- **Ordenações animadas**: o Merge Sort dividindo e recombinando a lista passo a passo, e uma corrida entre Merge, Quick, Insertion, Selection e Bubble Sort na mesma lista.
- **Desafio**: 10 funções sorteadas para identificar a complexidade, com correção e recorde salvo no navegador.
- **O olho do Big O**: clique no “O” do título e ele abre, acompanhando o cursor.
- **Um segredo**: com o olho aberto, arraste ele para o lado.

## Como abrir

Não precisa instalar nada. Baixe o repositório e abra o `index.html` no navegador.

Para publicar como site pelo GitHub Pages: no repositório, vá em **Settings → Pages**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e salve. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Detalhes técnicos

- Um único arquivo HTML, com CSS e JavaScript puros, sem frameworks e sem etapa de build.
- Nenhum dado sai do navegador. O único armazenamento é o recorde do desafio, guardado no `localStorage`.
- Política de segurança de conteúdo (CSP) restrita: o site só carrega fontes do Google Fonts e não faz nenhuma outra requisição externa.
- Funciona no celular, tem modo escuro automático, navegação por teclado e respeita a opção de reduzir movimento do sistema.

## Autores

- Davi Dandrea Siqueira
- Julia Zamoner
- Alvaro Danko
