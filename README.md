# 📘 Aula de HTML: Estrutura e Ferramentas 🔧🌐

Anotações da aula sobre HTML, com foco em estruturação, ferramentas e boas práticas para iniciantes.

---

## 👨‍🏫 Autor

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/79340989?s=400&u=fcfb57bc9a07b8ce0eeae1195e243bb1cb56f6d8&v=4" width=115><br><sub>Claudeny Avelino</sub>](https://github.com/ClaudenyAvelino)

---

## 🚀 Tecnologias

![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?\&style=for-the-badge\&logo=css3\&logoColor=white)

---

## 📑 Conteúdo da Aula

* [10-12 Acesse aqui](https://1drv.ms/b/c/c939bce3230fd75c/IQAi67qyRWcPRoDyKUgedX7OAb80oF-uW4C71sFnBBSSSps?e=cgAI1h)  

* [11-12 Acesse aqui](https://1drv.ms/b/c/c939bce3230fd75c/IQBvUoG6qqAsS6qMVrdv-T67ASrqWiu2tmAwY0YyAgxFFdk?e=hbmm1Y) 

### 1. A Importância da Documentação W3Schools 📚

A W3Schools é uma excelente fonte para aprender HTML e outras tecnologias web.
🔗 [Acesse W3Schools](https://www.w3schools.com/)

---

### 2. O que é HTML? 🤔

**HTML (HyperText Markup Language)** é uma linguagem de marcação usada para estruturar conteúdo na web. Ela **não executa ações**, apenas organiza elementos como:

* Textos
* Imagens
* Links
* Listas

---

### 3. Estrutura Básica de um Documento HTML 🏗️

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da Página</title>
</head>
<body>
  <h1>Isso é um título</h1>
  <p>Isso é um parágrafo</p>
  <img src="html.png" alt="Logo do HTML5">
</body>
</html>
```

---

### 4. A Utilidade da Tag `<!DOCTYPE html>` ⚙️

* Define o documento como HTML5.
* Evita o **Quirks Mode** (modo de compatibilidade antiga nos navegadores).

---

### 5. Diferença entre `<head>` e `<body>` 💡

* `<head>`: Contém **metadados** (título da aba, links de estilo, scripts).
* `<body>`: Contém o **conteúdo visível** da página.

---

### 6. Atributo `alt` nas Imagens 🖼️

Melhora a **acessibilidade** e o **SEO** do site.

```html
<img src="assets/claudeny.png" alt="Professor Claudeny">
```

---

### 7. Developer Tools 🔍

Ferramentas do navegador para:

* Inspecionar HTML/CSS
* Depurar erros
* Testar alterações em tempo real

Acessos rápidos:

* `F12`
* `Ctrl + Shift + I`

---

### 8. Quirks Mode 🤖

Modo de renderização "antigo".
**Você deve SEMPRE iniciar seus documentos HTML com:**

```html
<!DOCTYPE html>
```

---

### 9. Extensão Live Server no VS Code 🔌

Permite:

* Atualização automática da página no navegador
* Visualização em tempo real de alterações

**Como instalar:**

1. Abrir VS Code
2. Ir em Extensões (`Ctrl+Shift+X`)
3. Procurar por *Live Server*
4. Clicar em **Instalar**

---

### 🧱 Estrutura Semântica do HTML5

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Estrutura Semântica</title>
</head>
<body>

    <header>
        <!-- Cabeçalho: logo, menu, título principal -->
    </header>

    <nav>
        <!-- Navegação principal: links do menu -->
    </nav>

    <main>
        <!-- Conteúdo principal da página -->

        <section>
            <!-- Seção de conteúdos relacionados -->
        </section>

        <article>
            <!-- Conteúdo independente: postagem, notícia, artigo -->
        </article>

        <aside>
            <!-- Conteúdo lateral: anúncios, links extras, informações secundárias -->
        </aside>
    </main>

    <footer>
        <!-- Rodapé: direitos autorais, contatos, links adicionais -->
    </footer>

</body>
</html>
```
# Aula de Introdução ao HTML e CSS

## 1. O que é um Elemento HTML?

Um elemento HTML é a unidade fundamental de uma página da web. Ele é definido por uma **tag de abertura**, algum **conteúdo** e uma **tag de fechamento**.

**Exemplo de uma página HTML básica:**
```html
<!DOCTYPE html>
<html>
<body>

    <h1>Meu Primeiro Título</h1>
    <p>Meu primeiro parágrafo.</p>

</body>
</html>
```

---

## 2. Estrutura e Elementos Essenciais

### Parágrafos (`<p>`)
O elemento `<p>` é usado para definir um bloco de texto como um parágrafo.

**Exemplo:**
```html
<p>Este é um parágrafo.</p>
```

### Quebras de Linha (` `) e o Colapso do Espaço em Branco

Um dos conceitos mais importantes em HTML é que os navegadores **ignoram os espaços em branco e as quebras de linha** que você digita no seu código.

Por exemplo, o código abaixo, mesmo com uma linha em branco no meio:
```html
<p>
  Meu nome é Manus.

  Eu gosto de ajudar.
</p>
```
...será exibido em uma única linha no navegador: *Meu nome é Manus. Eu gosto de ajudar.*

Para forçar uma quebra de linha visualmente, você precisa usar a tag `<p>`. Ela instrui o navegador a "pular para a próxima linha" dentro do mesmo elemento.

**Exemplo com ` `:**
```
html
<p>Este é </p> 
<p>um parágrafo</p> 
<p>com quebras de linha.</p>
```
**Resultado no Navegador:**

Este é  

um parágrafo  

com quebras de linha.

**Quando usar `<p>`?** Use para quebras de linha que são parte do conteúdo, como em um endereço ou um poema. Para separar ideias diferentes, prefira usar parágrafos distintos (`<p>Texto 1</p><p>Texto 2</p>`).

### Linhas Horizontais (`<hr>`)
A tag `<hr>` cria uma linha horizontal que é usada para separar seções de conteúdo de forma visual.

**Exemplo:**
```html
<h1>Este é o título 1</h1>
<p>Este é um texto.</p>
<hr>
<h2>Este é o título 2</h2>
<p>Este é outro texto.</p>
```

---

## 3. Atributos HTML: Adicionando Informações aos Elementos

Atributos fornecem informações adicionais sobre os elementos e são sempre especificados na tag de abertura.

> **Boa prática:** Utilize sempre atributos com letras minúsculas para manter a consistência do seu código.

### O Atributo `src` (Source)
Usado principalmente em imagens (`<img>`) para especificar o caminho (URL) do arquivo de imagem.

**Exemplo:**
```html
<img src="img_girl.jpg">
```

### Atributos `width` e `height`
Definem a largura e a altura de um elemento, como uma imagem, em pixels.

**Exemplo:**
```html
<img src="img_girl.jpg" width="500" height="600">
```

### O Atributo `alt` (Alternative Text)
Fornece um texto alternativo para uma imagem, que é exibido se a imagem não puder ser carregada. É fundamental para a acessibilidade.

**Exemplo:**
```html
<img src="img_girl.jpg" alt="Garota com uma jaqueta">
```

### O Atributo `lang` (Language)
Especifica o idioma do conteúdo do documento. É declarado na tag `<html>` e ajuda os mecanismos de busca e navegadores.

**Exemplo:**
```html
<!DOCTYPE html>
<html lang="pt-br">
<body>
...
</body>
</html>
```

### O Atributo `title`
Adiciona um texto de "dica de ferramenta" (tooltip) que aparece quando o usuário passa o mouse sobre o elemento.

**Exemplo:**
```html
<p title="Eu sou uma dica de ferramenta">Este é um parágrafo.</p>
```

---

## 4. Formatação de Texto

HTML fornece elementos específicos para formatar o texto e dar a ele um significado semântico.

| Tag | Descrição | Exemplo |
| :--- | :--- | :--- |
| `<b>` | **Texto em negrito** (visual) | `<b>Este texto está em negrito</b>` |
| `<strong>` | **Texto importante** (semântico) | `<strong>Texto importante</strong>` |
| `<i>` | *Texto em itálico* (visual) | `<i>Texto em itálico</i>` |
| `<em>` | *Texto enfatizado* (semântico) | `<em>Texto enfatizado</em>` |
| `<mark>` | Texto marcado/realçado | `<mark>Texto marcado</mark>` |
| `<small>` | Texto menor | `<small>Texto menor</small>` |
| `<del>` | Texto excluído | `<del>Texto excluído</del>` |
| `<ins>` | Texto inserido | `<ins>Texto inserido</ins>` |
| `<sub>` | Texto subscrito (ex: H₂O) | `H<sub>2</sub>O` |
| `<sup>` | Texto sobrescrito (ex: X²) | `X<sup>2</sup>` |

---

## 5. Estilizando com CSS (Cascading Style Sheets)

Enquanto o HTML estrutura o conteúdo, o CSS é usado para estilizá-lo (cores, fontes, layout, etc.).

### O Atributo `style`
A forma mais direta de aplicar CSS é usando o atributo `style` em um elemento HTML.

**Exemplo de tamanho de fonte:**
```html
<h1 style="font-size:60px;">Título 1</h1>
```

### Cor de Fundo (`background-color`)
Define a cor de fundo de qualquer elemento.

**Exemplo:**
```html
<body style="background-color:powderblue;">
    <h1 style="background-color:powderblue;">Este é um título</h1>
    <p style="background-color:tomato;">Este é um parágrafo.</p>
</body>
```

### Cor do Texto (`color`)
Define a cor do texto dentro de um elemento.

**Exemplo:**
```html
<h1 style="color:blue;">Este é um título</h1>
<p style="color:red;">Este é um parágrafo.</p>
```

### Fontes (`font-family`)
Define a família da fonte para o texto.

**Exemplo:**
```html
<h1 style="font-family:verdana;">Este é um título</h1>
<p style="font-family:courier;">Este é um parágrafo.</p>
```

### Tamanho do Texto (`font-size`)
Controla o tamanho do texto. Pode ser em pixels (`px`) ou porcentagem (`%`).

**Exemplo:**
```html
<h1 style="font-size:300%;">Este é um título</h1>
<p style="font-size:160%;">Este é um parágrafo.</p>
```

### Alinhamento de Texto (`text-align`)
Define o alinhamento horizontal do texto (`left`, `right`, `center`).

**Exemplo:**
```html
<h1 style="text-align:center;">Título Centralizado</h1>
<p style="text-align:center;">Parágrafo Centralizado.</p>
```

---

## 6. Formatos de Cores em CSS

Existem várias maneiras de especificar cores em CSS.

### Cores RGB e RGBA
- **RGB**: Define uma cor usando os valores de Vermelho (Red), Verde (Green) e Azul (Blue), que variam de 0 a 255.
  - `rgb(255, 0, 0)` é vermelho puro.
  - `rgb(60, 60, 60)` é um tom de cinza escuro.
- **RGBA**: É o mesmo que RGB, mas com um canal **Alpha** (transparência) que vai de 0.0 (totalmente transparente) a 1.0 (totalmente opaco).
  - `rgba(255, 99, 71, 0.5)` é a cor "Tomato" com 50% de transparência.

### Cores Hexadecimais (HEX)
Um código de 6 dígitos precedido por `#`. Representa os mesmos valores RGB, mas no formato hexadecimal (`#RRGGBB`).
- `#ff0000` é vermelho puro.
- `#0000ff` é azul puro.
- `#ee82ee` é violeta.

---

## 7. Métodos de Aplicação de CSS

Existem três maneiras de incluir CSS em sua página.

### 1. CSS Embutido (Inline CSS)
Aplica um estilo único a um único elemento HTML usando o atributo `style`. É útil para alterações rápidas, mas não é recomendado para estilizar um site inteiro.

**Exemplo:**
```html
<h1 style="color:blue;">Um Título Azul</h1>
<p style="color:red;">Um parágrafo vermelho.</p>
```

### 2. CSS Interno (Internal CSS)
Define estilos para uma única página HTML. Os estilos são colocados dentro de uma tag `<style>` no `<head>` do documento.

**Exemplo:**
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body { background-color: powderblue; }
        h1   { color: blue; }
        p    { color: red; }
    </style>
</head>
<body>
    <h1>Este é um título</h1>
    <p>Este é um parágrafo.</p>
</body>
</html>
```

### 3. CSS Externo (External CSS)
É a maneira mais comum e recomendada. Você cria um arquivo separado com a extensão `.css` e o vincula a quantas páginas HTML desejar. Isso permite reutilizar estilos e facilitar a manutenção.

**Passo 1: Crie o arquivo `styles.css`**
```css
/* styles.css */
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

**Passo 2: Vincule o arquivo no seu HTML**
Use a tag `<link>` dentro do `<head>`.

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Este é um título</h1>
    <p>Este é um parágrafo.</p>
</body>
</html>
```

---

## 8. Comentários em HTML

Você pode adicionar comentários ao seu código para deixar notas ou desativar partes do código. Eles não são exibidos no navegador.

**Sintaxe:**
```html
<!-- Escreva seus comentários aqui -->
```

#Bons estudos!!
