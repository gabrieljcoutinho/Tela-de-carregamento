# Tela de Carregamento

# Custom CSS Loader (Spinner)

Este projeto apresenta uma implementação elegante e minimalista de um componente de carregamento (loader) utilizando apenas HTML e CSS puro. É uma solução leve e eficiente para indicar estados de espera ou processamento em aplicações web.

## Características do Componente

* **Puro CSS:** Sem necessidade de bibliotecas externas ou imagens pesadas, garantindo um carregamento instantâneo.
* **Animação Infinita:** Utiliza a diretiva `@keyframes` para criar um movimento de rotação suave e contínuo.
* **Design Moderno:** Estilo circular com bordas contrastantes e uma cor de destaque (`#51d4db`) que facilita a visualização sobre fundos claros ou escuros.
* **Centralização Absoluta:** Configurado com Flexbox no `body` para garantir que o loader esteja sempre perfeitamente centralizado na viewport, independente do tamanho do dispositivo.

## Tecnologias Utilizadas

* **HTML5:** Estrutura básica do componente.
* **CSS3:** Responsável por toda a lógica visual e de animação.
    * **Flexbox:** Para alinhamento e centralização.
    * **Keyframes:** Para a lógica de transformação `rotate`.

## Estrutura de Código

### HTML
A estrutura consiste em uma única `div` com a classe `.c-loader`, servindo como o elemento visual do spinner.

### CSS
O segredo deste loader está na propriedade `border`. Três lados do círculo recebem uma cor neutra, enquanto o `border-top-color` recebe a cor vibrante, criando o efeito de "faixa" que gira.



## Como Utilizar

1. Copie o HTML para o seu arquivo de estrutura.
2. Adicione o CSS ao seu arquivo de estilos principal ou em uma tag `<style>`.
3. Para alterar o tamanho, basta modificar as propriedades `height` e `width` na classe `.c-loader`.
4. Para alterar a velocidade, ajuste o tempo na propriedade `animation` (ex: `0.5s` para mais rápido).

---

<img width="461" height="201" alt="image" src="https://github.com/user-attachments/assets/e205665b-5659-4e4c-aa81-5671e4a148bc" />

