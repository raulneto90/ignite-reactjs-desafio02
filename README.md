# WatchMe - Trilha Ignite ReactJS

<img src="https://github.com/raulneto90/ignite-reactjs-desafio02/blob/main/images/system.gif" alt="WatchMe" align="center"/>

O WatchMe é um aplicativo de listagem de filmes baseados no gênero escolhido.

## 💻 Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é refatorar uma página para listagem de filmes de acordo com gênero. 

A aplicação já está totalmente funcional mas grande parte do seu código está diretamente no arquivo `App.tsx`. Para resolver isso da melhor forma, é necessário dividir a aplicação em **pelo menos** duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.

## O que devo editar na aplicação?

Com o template já clonado, as dependências instaladas e a [fake API rodando](https://www.notion.so/Desafio-01-Criando-um-hook-de-carrinho-de-compras-5769216778794019a83f544e79167b12), você deve criar **pelo menos** os componentes SideBar e Content que já estão com os arquivos criados.
Os arquivos a serem editados são:

- **src/App.tsx**
Esse componente contém toda a aplicação com exceção do componente `Button` que não precisa ser alterado e `Icon` que também não precisa de alteração.
- **src/components/Content.tsx**
Esse componente, ainda vazio, deve possuir toda a lógica e corpo responsável pelo header e conteúdo da aplicação (seção contornada em vermelho):

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ff7c8a12-50d1-4a20-a680-9085d0bd6823/example.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ff7c8a12-50d1-4a20-a680-9085d0bd6823/example.png)

- **src/components/SideBar.tsx**
Esse componente, também vazio, deve possuir toda a lógica e corpo responsável pela seção que contém o título do site e a parte de navegação à esquerda da página (seção contornada em vermelho):

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/88f057c2-d29a-4b0d-b9ed-f11385e09030/example.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/88f057c2-d29a-4b0d-b9ed-f11385e09030/example.png)

Se você preferir, pode também componentizar algumas outras partes da aplicação como, por exemplo, o header, mas esse não está como requisito deste desafio 🚀

## :floppy_disk: Como utilizar este projeto

Para baixar este projeto é necessário que esteja instalado em seu computador o NodeJS e o Yarn.
No terminal:

```bash
$ git clone https://github.com/raulneto90/ignite-reactjs-desafio02

# Acesse o diretório do projeto
$ cd ignite-reactjs-desafio02

# Instalar as dependências
$ yarn

# Executar o fake api
$ yarn server

# Executar o projeto em desenvolvimento
$ yarn dev
```
---
Feito com ❤ por Raul Neto. Me siga no [Linkedin](https://www.linkedin.com/in/raul-neto-777bb988/)