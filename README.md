<p align="center">
 <a href="#Description">Descrição</a> •
 <a href="#Features">características</a> • 
 <a href="#Technologies">Tecnologias</a> •
 <a href="#How to use">Como usar</a> •
 <a href="#Software">Software</a> 
</p>

Seleção - BitLab 2023 - Detector de textos impróprios

## Instruções
- 1 - Acesse a aplicação em: https://selecao-2023-jcassio-dev.vercel.app/;
- 2 - Digite no campo de texto, que tem escrito "digite seu texto aqui";
- 3 - Aperte em verificar texto;

- 3.1 - Caso o texto possua palavras ofensivas, ele irá retornar uma notificação dizendo quais foram as palavras ofensivas utilizas e vai censurá-las no texto digitado, substituindo as letras por asteriscos;
- 3.2 - Caso não seja observada nenhuma palavra ofensiva, o programa retornará uma notificação com a mensagem "Texto Seguro";

<div align="center">

https://user-images.githubusercontent.com/62391659/231556210-0193d78a-c9ef-4449-976f-687799e724bd.mp4

</div>
<div id="Description">

## Descrição
Projeto desenvolvido para a seleção do BitLab 2023, a proposta do projeto era desenvolver um detector de palavras ofensivas e de baixo calão dentro de um texto. Desenvolvi uma solução com base em uma lista de palavras impróprias já predefinidas, onde o texto do usuário passa por um filtro verificando sem alguma das palavras digitadas se encontra nessa lista. Caso encontre, o programa irá substituir as letras da palavra por "*" e retornará ao usuário quais foram as palavras de baixo calão utilizadas.

Todas as palavras a serem filtradas podem ser encontradas em src/utils/badWordList.ts
</div> 
<div id="Features">

### Aspectos

- [x] React
- [x] SPA
- [x] Responsiviness
- [x] Typing

</div>
<div id="Characteristics">

## Caracteristicas:
- React + Vite;
- Component elements;
- CSS-in-JS;
- global styles;
- Array methods;

</div>
<div id="Technologies">

## Tecnologias:

- Languages: `typescript` `CSS` `HTML`
- Libraries: `react` `react-icons` `styled-components` `react-toastify`
- Version control: `Git & Github`

</div>
<div id="How to use">

## Como usar localmente:

#### Clone esse repositório

```bash
$ git clone https://github.com/Jcassio-dev/ProfanityWords-API.git
```

#### Acesse a pasta do projeto no terminal/cmd

```bash
$ cd /ProfanityWords-API
```

#### Instale as dependências

```bash
$ npm install
```

#### Execute a aplicação no modo de desenvolvimento

```bash
$ npm run dev
```
#### O server será iniciado - Vá até a porta informada
```bash
localhost:port
```
</div>
<div id="Software">

## Software

VSCode
</div>
