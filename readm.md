# Como a Internet Chega na Minha Casa?

## 1. Como surgiu a internet?
- A internet surgiu durante a Guerra Fria.

### 1.1.1 DARPA e ARPANET
#### 1.1.1.1 DARPA
- A **Defense Advanced Research Projects Agency** (DARPA) realizou investimentos iniciais ao desenvolvimento de tecnologias como a criação da ARPANET.

#### 1.1.1.2 ARPANET
- Primeira rede de computadores.
- Criada para transmitir dados militares e interligar departamentos de pesquisa nos Estados Unidos.
- Incluía 4 tipos diferentes de computadores: SDS 90, SDS Sigma 7, IBM 370/75 e DEC PDP-10.
- Cada computador tinha uma linguagem própria, dificultando a comunicação.

## 1.2 NCP
- **Network Control Protocol**.
- Permitia a comunicação entre diferentes redes de computadores.
- Necessitava parar a rede para poder se comunicar.

## 1.3 TCP/IP
- **TCP** (Transmission Control Protocol) e **IP** (Internet Protocol).
- Resolveu o problema de parar a rede para comunicação.
- Atualmente, é o protocolo utilizado.

## 1.4 Como funciona a internet?
- Relacionamento cliente e servidor.
- O cliente faz uma solicitação (request).
- O servidor entrega o que foi solicitado como resposta (response).

## 1.5 Como era a internet?
- Utilizava o protocolo **GOPHER**.
- Navegação era feita apenas pelo teclado.

## 1.6 Surgimento da WWW
### 1.6.1 Tim Berners-Lee
- Criou o protocolo **HTTP** (Hypertext Transfer Protocol), **HTML** (Hypertext Markup Language) e a **WWW** (World Wide Web).

### 1.6.2 Marc Andreessen
- Criou o **Mosaic**, o primeiro navegador compatível com HTTP.

### 1.7 WWW não é a internet?
- A WWW é apenas mais uma sub-rede da internet, especializada em **HTTP**.

#### 1.7.1 A internet é composta por outros protocolos:
- **FTP**, **GOPHER**, **SMTP**, **POP3**, **IMAP**.

---

# 2. Como a Internet Funciona?

## 2.1 O que é bit e byte?
- **Bit** é representado por 0 ou 1.
- 0 representa ausência de sinal.
- 1 representa presença de sinal.
- A sequência de 8 bits forma 1 byte.

## 2.2 Servidor DNS
- Converte nomes de domínio em endereços IP, definindo qual servidor o usuário alcançará ao digitar um domínio no navegador.

---

# 3. Domínio e Hospedagem

## 3.1 Domínio
- É o endereço do site.
- Deve ser único.
- Existem vários **TLDs** (Top-Level Domain).

## 3.2 Hospedagem
- Espaço utilizado para armazenar os arquivos do site.

---

# 4. HTML, CSS e JavaScript


## 4.1 HTML (HyperText Markup Language)
- Define o conteúdo do site (texto, imagens, tabelas, vídeos, etc.).
![Tag HTML](../img/tagP.png)
![Estrutura HTML](../img/estrutura.png)

## 4.2 CSS (Cascading Style Sheets)
- Define o design e o estilo visual (cores, sombras, tamanhos, posicionamento, etc.).
![Estilo CSS](../img/estilo.png)

## 4.3 JavaScript (Linguagem de Programação)
- Responsável pelas interações, como menus, animações, popups e validações de formulários.

---

# 5. Parágrafo e Quebra de Linha no HTML5

## 5.1 Parágrafos

- Em HTML, os parágrafos são definidos com a tag `<p>`.
- A tag `<p>` cria um bloco de texto com margens automáticas ao redor.
- É usada para agrupar blocos de texto de forma semanticamente correta.
- A tag `<br> `é usada para inserir uma quebra de linha simples dentro do texto.
- Diferente da tag `<p>`, a tag `<br>` não cria um novo bloco, mas sim uma quebra dentro do mesmo bloco de texto.

### Exemplo de Uso:

```html
    <p>Este é um exemplo de parágrafo em HTML.</p>
    <p>Este é um parágrafo com uma quebra de linha<br>no meio do texto.</p>
```
---

# 6. HTML Entities

- Tags podem aparecer no navegador usando entidades HTML (códigos especiais).
- Exemplo: `<` (menor que) é representado por `&lt;`.
- Exemplo: `>` (maior que) é representado por `&gt;`.
![Outros HTML Entities](../img/entties.png)

### Exemplo de Uso:
```html
<p>Para exibir o caractere menor que, use &lt;. Para o caractere maior que, use &gt;.</p>
```

---


# 7. Uso da Tag `<img>`

A tag `<img>` é usada para exibir imagens em uma página web. Ela é uma tag auto-contida e não possui uma tag de fechamento.

## 7.1 Atributos Principais

- **`src`**: Define o caminho para o arquivo da imagem. Este atributo é obrigatório.
- **`alt`**: Fornece uma descrição alternativa da imagem, útil para acessibilidade e quando a imagem não pode ser carregada. Este atributo é recomendado.
- **`title`**: Exibe um texto quando o usuário passa o mouse sobre a imagem. Este atributo é opcional.
- **`width`** e **`height`**: Definem a largura e altura da imagem. Estes atributos são opcionais, mas é importante manter a proporção para evitar distorções.

## 7.2 Formatos de Imagem

- **JPEG (`.jpg`, `.jpeg`)**: Ideal para fotografias e imagens com muitos detalhes. Suporta compressão com perda, o que reduz o tamanho do arquivo.
- **PNG (`.png`)**: Ideal para imagens com fundo transparente e gráficos com cores sólidas. Suporta compressão sem perda.
- **GIF (`.gif`)**: Ideal para imagens animadas e gráficos simples com um número limitado de cores. Suporta animação e transparência, mas com menos qualidade do que o PNG.
- **SVG (`.svg`)**: Ideal para gráficos vetoriais e ícones. Pode ser escalado sem perda de qualidade, pois é baseado em vetores.

## Exemplo de Uso:

```html
<img src="caminho/para/imagem.jpg" alt="Descrição da Imagem" title="Texto de Dica" width="300" height="200">
<img src="caminho/para/imagem.jpg" alt="Fotografia de um parque" title="Imagem JPG">
<img src="caminho/para/imagem.png" alt="Logo da empresa" title="Imagem PNG">
<img src="caminho/para/imagem.gif" alt="Animação divertida" title="Imagem GIF">
<img src="caminho/para/imagem.svg" alt="Ícone de usuário" title="Imagem SVG">

```

# 8. Favicon de um Site

Um favicon é um pequeno ícone que aparece na aba do navegador ao lado do título da página. Ele ajuda a identificar visualmente o site e melhora a experiência do usuário.

## 8.1 Como Adicionar um Favicon

**Adicione o link para o favicon no `<head>` do seu HTML**: Use a tag `<link>` para referenciar o favicon. Aqui estão os exemplos para diferentes formatos de imagem:

## Exemplos de Código:

### Para um arquivo `.ico`:

```html
<head>
    <link rel="icon" type="image/x-icon" href="/caminho/para/favicon.ico">
</head>
```

### Para um arquivo `.png`:
```html
<head>
    <link rel="icon" type="image/png" href="/caminho/para/favicon.png">
</head>
```
### Para um arquivo `.svg`:
```html
<head>
    <link rel="icon" type="image/svg+xml" href="/caminho/para/favicon.svg">
</head>
```



# 9. Hierarquia de Títulos

- Títulos em HTML são chamados de **headings**.
- Existem seis níveis de headings.
- Usados para organizar o conteúdo da página.
- Somente um `<h1>` deve ser utilizado por página; os demais são subtítulos.

### Exemplo de Uso:
```html
<h1>Este é o título principal (H1)</h1>
<h2>Este é um subtítulo de segundo nível (H2)</h2>
<h3>Este é um subtítulo de terceiro nível (H3)</h3>
<h4>Este é um subtítulo de quarto nível (H4)</h4>
<h5>Este é um subtítulo de quinto nível (H5)</h5>
<h6>Este é um subtítulo de sexto nível (H6)</h6>
```

---

# 10. Semântica no HTML5 é Importante

- Semântica refere-se ao significado dos elementos, em vez de apenas sua forma.
- O significado tem mais importância do que a aparência.

## 10.1 HTML4 e HTML5
- No HTML4, o comportamento das tags era suficiente.
- No HTML5, o foco está em tags semânticas, priorizando o significado.

## 10.2 O Uso do CSS
- **CSS** cuida do estilo e da forma.
- O HTML não é mais responsável por alterar o design visual, como cores de texto ou o background; para isso, usa-se o CSS.

---

<!-- # 10. Links e Âncoras

## 10.1 Links
- São a essência fundamental do hipertexto.
- Conectam documentos.
- Permitem navegação entre páginas na web.

## 10.2 Âncoras (Hyperlinks)
- Permitem ligar um ponto a outro na **World Wide Web**. -->


# 11. Negrito e Itálico em HTML

## 11.1 Negrito

- Para aplicar negrito ao texto em HTML, você pode usar a tag `<strong>` ou a tag `<b>`.
- A tag `<strong>` não só aplica o estilo de negrito, mas também dá ênfase semântica ao texto, indicando que ele é importante.
- A tag `<b>` aplica o estilo de negrito, mas não possui significado semântico.

## 11.2 Itálico
- Para aplicar itálico ao texto em HTML, você pode usar a tag` <em> `ou a tag `<i>`.
- A tag `<em>` não só aplica o estilo de itálico, mas também dá ênfase semântica ao texto, indicando que ele deve ser lido com ênfase.
- A tag `<i>` aplica o estilo de itálico, mas não possui significado semântico.

### Exemplo de Uso:

```html
<p>Este é um texto com <strong>ênfase importante</strong> usando a tag <code>&lt;strong&gt;</code>.</p>
<p>Este é um texto com <b>negrito simples</b></p>
<p>Este é um texto com <em>ênfase importante</em></p>
<p>Este é um texto com <i>itálico simples</i></p>
``` 


# 12. Outras Formatações Adicionais em HTML

Além de negrito e itálico, HTML oferece várias outras opções de formatação para enriquecer o conteúdo da sua página web.

## 12.1 Sublinhado

- Para sublinhar texto, use a tag `<u>`.
- A tag `<u>` aplica um estilo de sublinhado ao texto, mas não possui significado semântico.

### Exemplo de Uso:

```html 
<p>Este é um texto com <u>sublinhado</u> usando a tag <code>&lt;u&gt;</code>.</p>
```

## 12.2 Riscar
- Para riscar texto, use a tag `<s>` ou `<del>`.
- A tag `<s>` aplica um estilo de riscar ao texto, mas não possui significado semântico.
- A tag `<del>` é usada para marcar texto que foi removido e é exibida com uma linha atravessada, indicando alterações no conteúdo.

### Exemplo de Uso:
```html
<p>Este é um texto com <s>texto riscado</s></p>
<p>Este é um texto com <del>texto deletado</del></p>
```

## 12.3 Superscrito e Subscrito
- Para aplicar o estilo de superscrito, use a tag `<sup>`.
- Para aplicar o estilo de subscrito, use a tag `<sub>`.

### Exemplo de Uso:
```html
<p>Este é um texto com <sup>superscrito</sup></p>
<p>Este é um texto com <sub>subscrito</sub></p>
```
# 12.4 Citações e Blocos de Citação
- Para citações em linha, use a tag `<q>`.
- Para blocos de citação, use a tag ``<blockquote>``.
- A tag `<q>` é usada para citações curtas e adiciona aspas automaticamente.
- A tag `<blockquote>` é usada para citações longas e é formatada com uma margem.

### Exemplo de Uso:
```html
<p>Esta é uma citação em linha usando a tag <q>como exemplo</q>.</p>
<blockquote>
    <p>Esta é uma citação em bloco. Ela é usada para exibir um bloco de texto em citação.</p>
    <footer> — Autor</footer>
</blockquote>
```

# 12.5 Código e Pré-formatado
- Para exibir código, use a tag `<code>`.
- Para exibir texto pré-formatado, use a tag `<pre>`.
- A tag `<code>` é usada para marcar trechos de código ou comandos.
- A tag `<pre>` é usada para preservar espaços e quebras de linha no texto, mantendo o formato original.

### Exemplo de Uso:
```html
<p>Este é um exemplo de <code>código</code> dentro de um parágrafo.</p>
<pre>
    <code>
function exemplo() {
    console.log("Texto pré-formatado");
}
    </code>
</pre>

```
# 13. Listas Ordenadas e Desordenadas em HTML

Listas são uma maneira eficaz de organizar informações em HTML. Existem dois tipos principais de listas: ordenadas e desordenadas.

## 13.1 Listas Ordenadas

- Listas ordenadas são usadas quando a ordem dos itens é importante.
- São definidas com a tag `<ol>`, e cada item é marcado com a tag `<li>`.
- Os itens da lista são automaticamente numerados pelo navegador.
- É possível especificar o tipo de numeração usando o atributo `type`.

### 13.1.1 Tipos de Numeração:

- **`type="1"`**: Números (1, 2, 3, …). Este é o padrão.
- **`type="A"`**: Letras maiúsculas (A, B, C, …).
- **`type="a"`**: Letras minúsculas (a, b, c, …).
- **`type="I"`**: Números romanos maiúsculos (I, II, III, …).
- **`type="i"`**: Números romanos minúsculos (i, ii, iii, …).


### Exemplo de Uso:

```html 
<ol>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <li>Terceiro item</li>
</ol>
```

## 13.2 Listas Desordenadas
- Listas desordenadas são usadas quando a ordem dos itens não é importante.
- São definidas com a tag `<ul>`, e cada item é marcado com a tag `<li>`.
- Os itens da lista são precedidos por marcadores (geralmente pontos).

### 13.1.1 Tipos de Marcadores:
- **`type="disc"`**: Marcador sólido (•). Este é o padrão.
- **`type="circle"`**: Marcador vazio (◯).
- **`type="square"`**: Marcador quadrado (▪).

### Exemplo de Uso:

```html 
<ul>
    <li>Item um</li>
    <li>Item dois</li>
    <li>Item três</li>
</ul>

```

# 13.3 Listas Aninhadas
- Listas podem ser aninhadas dentro de outras listas para criar sublistas.
- Isso pode ser feito usando uma `<ul>` ou `<ol>` dentro de um item `<li>` de outra lista.

### Exemplo de Uso:

```html 
<ol>
    <li>Primeiro item
        <ul>
            <li>Subitem um</li>
            <li>Subitem dois</li>
        </ul>
    </li>
    <li>Segundo item</li>
</ol>

```
# 14. Links e Âncoras em HTML

Links e âncoras são essenciais para a navegação entre páginas e seções em HTML. Eles permitem criar conexões e referências dentro de um site e entre sites.

## 14.1 Links

- Links são criados usando a tag `<a>`.
- A tag `<a>` é usada para criar um link que direciona o usuário para outra página, um endereço externo, ou uma âncora dentro da mesma página.
- O atributo principal da tag `<a>` é `href`, que define o destino do link.

### Atributos Importantes:

- **`href`**: Define o destino do link. Pode ser um URL, um caminho relativo para uma página no mesmo site, ou uma âncora dentro da mesma página.
- **`target`**: Define como o link será aberto. Pode ter os seguintes valores:
  - **`_self`**: Abre o link na mesma janela/aba (padrão).
  - **`_blank`**: Abre o link em uma nova janela/aba.
  - **`_parent`**: Abre o link na janela/aba pai, se houver um `<iframe>` envolvido.
  - **`_top`**: Abre o link na janela/aba principal, substituindo qualquer `<iframe>`.
- **`rel`**: Define a relação entre a página atual e o link. Usado principalmente para melhorar a segurança e SEO. Exemplos:
  - **`nofollow`**: Indica que os motores de busca não devem seguir o link.
  - **`noopener`**: Melhora a segurança ao abrir links em novas abas, evitando que a nova página possa acessar a página original.
  - **`noreferrer`**: Impede o envio de informações sobre a origem do link ao site de destino.

### Exemplo de Uso:

```html
<a href="https://www.example.com" target="_blank" rel="noopener noreferrer">Visite o Example.com</a>
```
