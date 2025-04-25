# TrioMap

TrioMap é um projeto web responsivo que permite comparar rotas entre três locais distintos em um mapa interativo, afim de calcular distâncias e tempo estimado de trajeto para realizar comparativos.

## Funcionalidades
- Escolha 3 locais via clique no mapa ou input de texto
- Cálculo de rota de A para B e de A para C
- Distância e tempo estimado com base no modo de transporte
- Botão de reset para limpar inputs e marcadores
- Layout responsivo e intuitivo
- Instalável como Progressive Web App (PWA)

## Tecnologias utilizadas
- HTML, CSS, JavaScript
- [Leaflet.js](https://leafletjs.com/) para mapa interativo
- [OpenRouteService](https://openrouteservice.org/) para geocodificação e rotas
- Service Worker + Manifest para PWA

## Planejamento de Desenvolvimento

### Etapa 1:Criação do Protótipo e Design
**Objetivo:** Criar os protótipos de interface.
- Defina a interface de usuário (UI), com base na experiência do usuário (UX).
- Considere responsividade e acessibilidade na aplicação.

### Etapa 2: Desenvolvimento da Estrutura Básica
**Objetivo:** Começar a construção da base do projeto.
- Desenvolvimento dos arquivos HTML, CSS e JavaScript

### Etapa 3: Integração com Mapas
**Objetivo:** Integrar com a API de mapa escolhida (ex.: Google Maps, Leaflet).
- Adicionar o mapa básico ao frontend, com funcionalidades como zoom, rotação, e marcadores.
- Implementar interatividade básica, como cliques nos mapas e exibição de informações sobre a localização selecionada.

### Etapa 4: Funcionalidades Principais
**Objetivo:** Implementar as funcionalidades principais para a utilização do projeto.
- Exibição de trilhas ou pontos de interesse no mapa.
- Funcionalidades de busca de locais ou trilhas.

### Etapa 5: Ajustes Finais e Polimento
**Objetivo:** Refinar a aplicação para produção.
- Melhorias no design e no layout.
- Melhorias de desempenho (ex: lazy loading de imagens ou dados, otimização de código).
