# Controle de Materiais - Almoxarifado

Link do projeto publicado: colocar o link aqui depois do deploy.

## Sobre o projeto

Este projeto é um sistema simples para controle de materiais de um almoxarifado. A ideia é ajudar no cadastro, consulta, retirada e exclusão de itens do estoque, deixando o controle mais fácil do que fazer tudo em planilha ou anotação manual.

O sistema foi feito para a atividade da Sprint 1, Sprint 2 e Sprint 3, usando a MockAPI para salvar e buscar os dados.

## Funcionalidades

- Cadastrar materiais no estoque;
- Listar os materiais cadastrados;
- Buscar materiais pelo nome;
- Mostrar o total de itens cadastrados;
- Dar baixa na quantidade do estoque;
- Impedir retirada negativa ou maior que a quantidade disponível;
- Excluir materiais;
- Marcar visualmente itens com estoque abaixo de 10 unidades.

## Tecnologias usadas

- HTML;
- CSS;
- JavaScript;
- MockAPI.

## API utilizada

O projeto utiliza a MockAPI com o recurso `estoque`.

Endpoint:

```text
https://6a31bda67bc5e1c61266204a.mockapi.io/av1/estoque
```

Estrutura dos dados:

```json
{
  "id": "1",
  "nome": "nome do material",
  "quantidade": 20
}
```

## Como rodar

1. Baixe ou clone este repositório;
2. Abra a pasta do projeto no VS Code;
3. Abra o arquivo `index.html` no navegador;
4. Use o formulário para cadastrar materiais;
5. Teste a listagem, busca, baixa de estoque e exclusão.

Não precisa instalar nada, pois o projeto usa apenas HTML, CSS e JavaScript.

## Contrato técnico usado

Foram mantidos os IDs e classes pedidos na atividade:

```text
input-nome
input-quantidade
btn-cadastrar
lista-materiais
input-retirada
btn-baixar
btn-excluir
input-busca
total-itens
estoque-critico
```

## Observação

Para o sistema funcionar corretamente, é necessário estar conectado à internet, pois os dados são buscados e atualizados na MockAPI.

## Autor

Eduardo Fuse
