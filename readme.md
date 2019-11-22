<p align="center">
    <img height="300px" src="https://i.imgur.com/bhNJn9I.jpg" alt="Logo">
  <h3 align="center">Tea Template</h3>
</p>

<br />

## Sobre o Projeto

Um template com o objetivo de acelerar o processo de criação de um projeto, disponibilizando ferramentas como styled-components e absolute path ja configuradas e uma estrutura de projeto bem definida.

<br />

## Utilizando

Antes de usar em algum projeto, se atente às informações abaixo:

<br />

### Estrutura de Arquivos

A estrutura de arquivos está organizada da seguinte forma:

```bash
    TeaTemplate
    ├── src/
    │   │
    │   ├── assets/
    │   │   │
    │   │   └── Logo/
    │   │       │
    │   │       └── Logo.png
    │   │
    │   ├── components/
    │   │
    │   ├── helpers/
    │   │   │
    │   │   ├── colors/
    │   │   │   └── index.js
    │   │   │ 
    │   │   └── images/
    │   │       └── index.js
    │   │ 
    │   ├── pages/ 
    │   │   │
    │   │   └── Main/
    │   │       │
    │   │       ├── index.js
    │   │       │
    │   │       └── styles.js
    │   │ 
    │   ├── routes/
    │   │   │
    │   │   └── index.js
    │   │ 
    │   └── index.js
    │
    ├── .eslintrc.js
    │
    ├── .gitattributes
    │
    ├── .gitignore
    │
    ├── dependencies.json
    │
    ├── devDependencies.json
    │
    ├── index.js
    │
    ├── LICENSE
    │
    ├── package.json
    │
    └── README.md
```

<br />

### Instalação

1. Para instalar e utilizar esse template o processo é bem simples, basta criar um projeto novo utilizando o comando:

```sh
    react-native init Example --template tea-template
```

2. Depois do projeto criado você pode deletar o arquivo `App.js` da raiz, pois o arquivo `index.js` agora aponta para a pasta **src**.

Com isso o projeto será criado com todas as dependências do template devidamente instaladas e linkadas, tal como os arquivos de configuração que são copiados para o projeto.

<br />

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
