# Radar SEASIC — Módulo de Processos

Painel público e independente para acompanhamento consolidado de processos e projetos da SEASIC.

Esta entrega é uma etapa autônoma do projeto. Ela não substitui nem atualiza o Radar Gabinete atualmente publicado e poderá ser integrada ao projeto principal no futuro.

Base publicada: data-base de 17/07/2026.

## Conteúdo

- `index.html`: interface principal do módulo de processos.
- `mapa-sergipe.html`: visualização territorial incorporada ao painel.
- `seasic-data.js`: base consolidada utilizada pelas visualizações.
- `support.js`: runtime necessário para renderização da interface.
- `.nojekyll`: instrui o GitHub Pages a publicar os arquivos diretamente.

## Limitações atuais

- O painel funciona como consulta e protótipo navegável.
- Alterações realizadas na interface não são persistidas em banco de dados.
- Não há autenticação ou controle de acesso.
- Os dados de `seasic-data.js` ficam publicamente acessíveis no GitHub Pages.
- O mapa utiliza Leaflet, OpenStreetMap e recursos externos carregados pela internet.
