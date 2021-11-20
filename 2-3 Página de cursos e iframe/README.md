<h1 align="center">
    <img alt="Launchbase" src="https://storage.googleapis.com/golden-wind/bootcamp-launchbase/logo.png" width="400px" />
</h1>

<h3 align="center">
  Desafio 2-3: Página de cursos e iframe
</h3>

<blockquote align="center">“Você nunca sai perdendo quando ganha conhecimento!”</blockquote>

<p align="center">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%23F8952D">
  </a>

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

A partir do arquivo do desafio 2.2, adicionar no header um link chamado Conteúdos. Essa página deve conter um grid onde devem ser mostrados os 3 cursos da Rocketseat ([Cursos](https://www.rocketseat.com.br/)). Ao clicar em um dos cursos, deve ser aberta uma modal onde um iframe irá carregar as informações do curso selecionado.

### Informações da página

- Título da página
- Grid com 3 colunas e 1 linha onde serão apresentados os cards dos cursos

## Informações do card

- Imagem de destaque do curso ([Tutorial de como pegar os links das imagens](https://youtu.be/f4aS9ZULm4A))
- Título do curso
- Valor do curso
- Inscrição no curso

## Modal

O modal deve conter um iframe que busca a página do curso (dica: basta adicionar o Slug - versão padronizada do título - ao final de `https://www.rocketseat.com.br/`, por exemplo, `axios-um-cliente-http-full-stack`). Além do botão de fechar o modal, é preciso implementar a funcionalidade de maximizar o modal (dica: utilize a mesma lógica implementada para fechar o `modalOverlay`, mas trabalhe com a classe `modal` e utilize o método `contains` do `classList` para verificar se o elemento está ou não com a classe `maximize`).

### Estilização

Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

- Deve ser utilizado o grid para organizar os cursos
- O modal nunca deve abrir maximizado

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../LICENSE) para mais detalhes.

---

Feito com :purple_heart: by [Raphael Caires](https://github.com/raphaelcaires).
