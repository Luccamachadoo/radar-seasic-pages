# Almoxarifado SEASIC

Painel estático para consulta consolidada da Base Mestre do Almoxarifado da SEASIC.

Base publicada: atualização de 20/07/2026, com 1.098 pedidos e 409 itens cadastrados.

## Conteúdo

- `index.html`: interface principal do painel.
- `seasic-data.js`: dados consolidados exibidos pela interface.
- `support.js`: runtime necessário para renderizar o protótipo.
- `.nojekyll`: instrui o GitHub Pages a publicar os arquivos diretamente.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub, preferencialmente chamado `almoxarifado-seasic`.
2. Envie todos os arquivos desta pasta para a raiz da branch principal.
3. Nas configurações do repositório, acesse **Pages**.
4. Selecione a publicação a partir da branch principal e da pasta raiz.
5. Aguarde o GitHub informar o endereço público gerado.

## Atualização dos dados

Para atualizar os registros apresentados pelo painel, substitua `seasic-data.js` por uma nova versão que preserve a exportação `DATA`.

## Limitações atuais

- O painel funciona como consulta e protótipo navegável.
- Entradas, saídas e parâmetros digitados não são persistidos.
- Não há autenticação ou controle de acesso.
- Os dados contidos em `seasic-data.js` ficam acessíveis aos visitantes do site publicado.
- O carregamento da interface utiliza bibliotecas externas hospedadas no unpkg e fontes do Google Fonts.
