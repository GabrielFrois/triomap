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

## Como usar
1. Clone o repositório
2. Adicione sua chave da API OpenRouteService no código
3. Coloque os ícones `icon-192.png` e `icon-512.png` na raiz
4. Rode o projeto localmente com um servidor (Live Server, http-server etc.)
5. Acesse pelo navegador e adicione à tela inicial para instalar como app

## Instalação como PWA
O site pode ser instalado em dispositivos móveis e desktops modernos:
- No Chrome: clique em "Instalar app" na barra de endereço
- No Android: ao acessar, será oferecida a opção "Adicionar à Tela Inicial"

