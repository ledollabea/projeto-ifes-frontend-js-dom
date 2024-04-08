# Projeto Manipulando o Javascript DOM

Este é um projeto simples de manipulação de javascript DOM.

## Como Funciona

1. Abra o arquivo `index.html` em seu navegador.
2. Através do JS DOM, é selecionado o elemento cujo ID é header-nav;.
3. Através do JS DOM, são selecionados todos os elementos que contenham a classe bg-color-dark. 
  1. Posterior a isso, (usando setTimeout de 5 segundos) serão modificados todos os elementos inserindo um novo texto. A descrição do texto será "Manipulado #, onde # corresponde ao índice do elemento dentro do NodeList.


## Explicação do requisito de projeto 4

5. Caso rodado o código:
<script>
  let navs = document.querySelectorAll('nav');
    for(let k=0;k<navs.length;k++) {
      navs[k].innerHTML = "Novo texto";
    }
</script>
Resposta: Ambas as tags nav teriam seu conteúdo substituído por "Novo Texto".


## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `index.html`: Página onde estará todo o código, seja o HTML ou o script JS.

## Como Contribuir

Se você deseja contribuir com este projeto, siga estas etapas:

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adicione uma nova feature'`.
4. Faça push para a sua branch: `git push origin minha-feature`.
5. Envie um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).