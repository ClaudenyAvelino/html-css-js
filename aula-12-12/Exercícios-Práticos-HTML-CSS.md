# 5 Exercícios Práticos de HTML e CSS

Estes exercícios foram criados para consolidar os conceitos aprendidos na aula de Introdução ao HTML e CSS.

---

## Exercício 1: Estrutura Básica e Semântica de Texto

**Objetivo:** Criar a estrutura fundamental de uma página HTML e usar tags básicas de texto.

**Instruções:**
1.  Crie um novo arquivo chamado `ex1_biografia.html`.
2.  Adicione a estrutura básica do HTML (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
3.  Dentro do `<body>`, crie um título principal (`<h1>`) com o seu nome.
4.  Crie um parágrafo (`<p>`) de introdução sobre você.
5.  Crie um subtítulo (`<h2>`) chamado "Minhas Habilidades".
6.  No parágrafo abaixo do subtítulo, use a tag `<strong>` para destacar uma habilidade importante e a tag `<em>` para enfatizar um objetivo.
7.  Use a tag `<hr>` para separar o título principal do restante do conteúdo.

**Código de Exemplo (Estrutura):**
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>Minha Biografia</title>
</head>
<body>
    <!-- Seu código aqui -->
</body>
</html>
```

---

## Exercício 2: Atributos e Imagens

**Objetivo:** Adicionar uma imagem à página e praticar o uso de atributos essenciais.

**Instruções:**
1.  Continue usando o arquivo `ex1_biografia.html` ou crie um novo.
2.  Adicione a tag de imagem (`<img>`) em algum lugar do `<body>`.
3.  Defina o atributo `src` para uma imagem online (você pode usar um link de imagem de placeholder, como `https://via.placeholder.com/200`).
4.  Defina o atributo `alt` com uma descrição clara da imagem.
5.  Use os atributos `width` e `height` para definir o tamanho da imagem para 200 pixels de largura e 200 pixels de altura.
6.  Adicione o atributo `title` ao seu `<h1>` do Exercício 1, com o texto "Página Pessoal".

**Conceitos Chave:** `<img>`, `src`, `alt`, `width`, `height`, `title`.

---

## Exercício 3: CSS Embutido (Inline) e Formatação Específica

**Objetivo:** Aplicar estilos diretamente em elementos específicos usando o atributo `style`.

**Instruções:**
1.  No seu arquivo, encontre o `<h1>` (seu nome). Use o atributo `style` para:
    *   Mudar a cor do texto para `blue`.
    *   Mudar o tamanho da fonte para `40px`.
2.  No parágrafo de introdução (`<p>`), use o atributo `style` para:
    *   Mudar a cor de fundo (`background-color`) para `yellow`.
3.  Use a tag `<mark>` para realçar uma palavra no seu texto.
4.  Use a tag `<sub>` e `<sup>` para escrever a fórmula da água (H₂O) e um número ao quadrado (X²).

**Conceitos Chave:** `style` (inline CSS), `color`, `font-size`, `background-color`, `<mark>`, `<sub>`, `<sup>`.

---

## Exercício 4: CSS Interno e Cores (HEX e RGB)

**Objetivo:** Aplicar um tema visual consistente à página usando CSS interno e diferentes formatos de cor.

**Instruções:**
1.  Remova todos os estilos `style="..."` que você adicionou no Exercício 3.
2.  Dentro da tag `<head>`, adicione a tag `<style>`.
3.  Dentro da tag `<style>`, defina as seguintes regras:
    *   Para o `<body>`: Defina o `background-color` usando um código HEX (ex: `#f0f0f0` para cinza claro).
    *   Para o `<h1>`: Defina a `color` usando um valor RGB (ex: `rgb(0, 100, 0)` para verde escuro) e centralize o texto (`text-align: center;`).
    *   Para o `<h2>`: Defina a `font-family` para `Courier New`.
4.  Verifique se o estilo é aplicado a toda a página.

**Conceitos Chave:** CSS Interno (`<style>`), `background-color`, `color` (HEX e RGB), `text-align`, `font-family`.

---

## Exercício 5: Quebras de Linha e Comentários

**Objetivo:** Praticar o uso correto de `<br>` e adicionar comentários para documentação.

**Instruções:**
1.  Crie uma nova seção com um `<h2>` chamado "Meu Endereço".
2.  Crie um parágrafo (`<p>`) para o endereço. Dentro deste parágrafo, use a tag `<br>` para quebrar as linhas do endereço, como se fosse um envelope:
    *   Rua Exemplo, 123<br>
    *   Bairro Central<br>
    *   Cidade, Estado - CEP
3.  No final do seu arquivo HTML, adicione um **comentário HTML** explicando o que a tag `<hr>` faz.

**Código de Exemplo (Endereço):**
```html
<h2>Meu Endereço</h2>
<p>
    Rua Exemplo, 123<?>
    Bairro Central<?>
    Cidade, Estado - CEP
</p>
```

**Conceitos Chave:** `<br>` (uso correto), Comentários HTML (`<!-- -->`).

# Bons estudos!!
