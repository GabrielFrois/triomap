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
- Desenvolvimento dos arquivos HTML, CSS e JavaScript para criar a estrutura inicial da página.
  - HTML: Criar o esqueleto básico da página, incluindo as seções de mapa, navegação, e rodapé.
  - CSS: Estilizar a interface para torná-la visualmente agradável e responsiva. Usar práticas de design adaptativo.
  - JavaScript: Implementar a estrutura inicial para o mapa (ex.: integração com a API de mapas) e as interações iniciais.

### Etapa 3: Integração com Mapas
**Objetivo:** Integrar com a API de mapa escolhida (ex.: Google Maps, Leaflet).
- Integrar a API de mapas selecionada no frontend.
- Adicionar o mapa básico, permitindo funcionalidades como zoom, rotação e marcação de pontos de interesse.
- Implementar interatividade básica, como cliques no mapa para exibir informações sobre a localização selecionada.

### Etapa 4: Funcionalidades Principais
**Objetivo:** Implementar as funcionalidades principais para a utilização do projeto.
- Exibir trilhas ou pontos de interesse no mapa, com base nas informações fornecidas.
- Implementar funcionalidades de busca de locais ou trilhas, com filtragem ou sugestões.
- Implementar interação mais avançada com o mapa, calculando a distância e tempo de percurso.

### Etapa 5: Conversão para Mobile através de PWA
**Objetivo:** Adaptar a aplicação para ser uma Progressive Web App (PWA), garantindo que funcione de forma otimizada em dispositivos móveis.
- Criar o arquivo manifest.json, configurando ícones, nome do aplicativo e outras informações necessárias para o PWA.
- Implementar o Service Worker para permitir o cache de conteúdo e garantir que o aplicativo funcione offline ou com conectividade limitada.
- Adicionar a capacidade de instalar o aplicativo no dispositivo móvel, permitindo que o usuário adicione a PWA à tela inicial.

### Etapa 6: Ajustes Finais e Polimento
**Objetivo:** Refinar a aplicação para produção.
- Melhorias no design e no layout.
- Melhorias de desempenho (ex: lazy loading de imagens ou dados, otimização de código).
