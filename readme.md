# Sistema de Mapa com Roteamento Dinâmico (FIEC)
## 📌 Descrição

Este projeto é um sistema web de mapa interativo utilizando Leaflet.js e Leaflet Routing Machine. Ele permite:

    - Visualizar a localização da FIEC com um ícone personalizado (logo);
    - Calcular a rota dinâmica da posição atual do usuário até a FIEC;
    - Atualização em tempo real do percurso, onde a linha da rota vai desaparecendo à medida que o usuário se move;
    - Escolher o modo de transporte: 🚗 carro, 🚴 bicicleta ou 🚶 a pé;
    - Popup informativo da FIEC com endereço, logo e link para o site.

## 🌐 ⚠️ Importante: Executar Dentro do WAMP
Para que o sistema funcione corretamente, ele precisa estar dentro da pasta de hospedagem do seu servidor local WAMP.
# 📂 Caminho padrão:
    - C:\wamp64\www
    - C:\wamp64\www\leaflet\
    - http://localhost/leaflet/home.html
    - Instale o Leaflet na pasta do projeto.
    
## ✅ Instalação do Leaflet
    - Baixe o Leaflet 👉 https://leafletjs.com/download.html
    - Instale ele na pasta do projeto
    - Na pasta do projeto utilize o comando ```npm install leaflet```
    - Dentro do head coloque os comandos abaixo na ordem

```<link rel="stylesheet" href="node_modules/leaflet/dist/leaflet.css" />```
```<script src="node_modules/leaflet/dist/leaflet.js"></script>```

## 🚀 Funcionalidades
    - 📍 Mapa com marcador personalizado da FIEC;
    - 🔗 Popup informativo sempre aberto, com endereço, logo e link do site;
    - 📡 Roteamento dinâmico em tempo real baseado na localização do usuário;
    - 🔵 Linha azul da rota vai diminuindo conforme o deslocamento;
    - 🚥 Controle de modos de transporte;
     -🧭 Ícone do usuário com seta rotativa mostrando a direção do movimento.

## 🏗️ Tecnologias Utilizadas
    - HTML5, CSS3 e JavaScript
    - Leaflet.js (mapas interativos)
    - Leaflet Routing Machine (rotas)
    - OpenStreetMap (mapas gratuitos)
    - OSRM API (roteamento)

## ⚙️ Requisitos
    - Navegador com suporte a Geolocalização.
    - Permitir acesso à localização para funcionamento correto.
    - Conexão com a internet (para carregar mapas do OpenStreetMap e usar a API OSRM).

## 📜 Documentação Oficial
    - 🔗 https://leafletjs.com/

## 👨‍💻 Desenvolvido por
    - Luiz Germano

