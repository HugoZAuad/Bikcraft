📋 **Sumário**

* [🔍 Visão Geral](#visão-geral)
* [📂 Estrutura do Projeto](#estrutura-do-projeto)
* [🎨 Arquivos de Imagem](#arquivos-de-imagem)
* [📄 `index.html`](#indexhtml)
* [💅 `style.css`](#stylecss)
* [⚙️ Tecnologias Utilizadas](#tecnologias-utilizadas)
* 🚀 Como Usar](#como-usar)


🔍 **Visão Geral**

Este projeto demonstra a construção de uma página web simples para a marca fictícia "BikeCraft", apresentando a bicicleta elétrica "Nimbus Stark".  O foco principal é o posicionamento de elementos utilizando CSS, incluindo conceitos como grid layout. O projeto utiliza HTML para estrutura, CSS para estilização e SVG para os ícones.

📂 **Estrutura do Projeto**

```
0309 - POSICIONAMENTO EXERCICIO/
├── img/
│   ├── bikcraft.svg
│   ├── eletrica.svg
│   ├── rastreador.svg
├── index.html
└── style.css
```

🎨 **Arquivos de Imagem**

* **`img/bikcraft.svg`**: Logotipo da BikeCraft em formato SVG.
* **`img/eletrica.svg`**: Ícone de um relâmpago representando a motorização elétrica, em formato SVG com gradiente de laranja para vermelho.
* **`img/rastreador.svg`**: Ícone de um alvo representando o rastreador, em formato SVG com gradiente de laranja para vermelho.

📄 **`index.html`**

Este arquivo contém a estrutura HTML da página, incluindo:

* **Menu de navegação:** Com links para as seções da página (ainda não funcionais neste exemplo).
* **Seção de introdução:** Apresenta a "Nimbus Stark" com uma imagem e breve descrição.
* **Seção de vantagens:** Destaca os benefícios da bicicleta, como motor elétrico, velocidade e rastreador, utilizando os ícones SVG.
* **Rodapé:** Com informações de copyright.

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bikcraft - Nimbus Stark</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
    </body>
</html>
```

💅 **`style.css`**

Este arquivo contém as regras CSS que estilizam a página. Alguns destaques incluem:

* **Tipografia:** Define as fontes e tamanhos de texto.
* **Layout em Grid:**  Utilizado para organizar os elementos na página de forma responsiva.
* **Cores:** Utiliza uma paleta de cores neutras com destaque para o laranja (#e21).
* **Estilos para elementos específicos:** Define estilos para o menu, imagens, botões e rodapé.

```css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  display: grid;
}
```

⚙️ **Tecnologias Utilizadas**

* **HTML:**  Estrutura da página web.
* **CSS:**  Estilização da página.
* **SVG:**  Imagens vetoriais.


🚀 **Como Usar**

1. **Faça o download do projeto:** Clone o repositório ou baixe o arquivo ZIP.
2. **Abra o arquivo `index.html`:**  Abra o arquivo em um navegador web para visualizar a página.

Exemplo de código HTML demonstrando a inclusão de um dos ícones:

```html
<img src="img/eletrica.svg" alt="Ícone de elétrica">
```


Este projeto serve como um exemplo básico de posicionamento com CSS e pode ser expandido com mais funcionalidades e conteúdo.
