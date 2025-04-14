<h1 align="center"> Conversor de Moedas </h1>

<p align="center">
Projeto prático desenvolvido com HTML, CSS e JavaScript para treinar manipulação de formulários, eventos e lógica de conversão de valores em tempo real.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=0F172A&labelColor=1D4ED8">
</p>

<br>

<p align="center">
  <img alt="Preview do projeto desenvolvido." src="https://github.com/user-attachments/assets/88e159d5-14e5-48b3-b0bc-66b7b5ff50a1" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML5
- CSS3
- JavaScript

## 💻 Projeto

Este projeto consiste em um conversor de moedas que recebe um valor em uma moeda estrangeira (como dólar, euro ou libra) e converte automaticamente para reais, exibindo o resultado formatado na tela.

Durante o desenvolvimento, foram abordadas as seguintes práticas e conceitos:

- Criação do arquivo `script.js` e organização correta do carregamento no HTML para otimizar o desempenho.
- Captura do valor digitado em um campo de input e exibição no console para validação.
- Utilização de expressões regulares para garantir que o campo aceite apenas números, aumentando a confiabilidade da entrada.
- Captura da moeda selecionada pelo usuário através de um input tipo `select`, utilizando o evento de `submit`.
- Implementação da função `convertCurrency`, com parâmetros para valor total, valor da moeda e símbolo correspondente.
- Uso de `switch/case` para identificar a moeda e aplicar a conversão de forma dinâmica.
- Exibição e ocultação do elemento `footer` de forma dinâmica com adição/remoção de classes CSS.
- Manipulação do DOM para exibir o valor da cotação com interpolação de strings.
- Criação de função personalizada para formatação de valores monetários no padrão brasileiro (R$), com `toLocaleString`.
- Cálculo do valor total convertendo o valor e multiplicando pela cotação, exibindo o resultado formatado.
- Testes práticos com diferentes moedas (dólar, euro, libra) para garantir o funcionamento completo da aplicação.

O projeto reforça conceitos fundamentais de JavaScript como eventos, manipulação de elementos HTML, uso de funções reutilizáveis e tratamento de dados do formulário. Um ótimo exercício de integração entre lógica e interface.

## :memo: Licença

Este projeto está sob a licença MIT.

