# Hero Section <!--{ as="image" mode="hero" src="assets/exemplo.jpeg" }-->
#### Como gerar storytelling de impacto! <!--{ style="font-size:1rem;opacity:0.7;margin-top:1rem;" }-->


## Minha Historia

Aqui eu escrevo a introdução da minha história. 

## Essa é a minha segunda seção 

Aqui vou falar um pouco mais sobre o context o objetivos

## SDGs

Aqui vou elencar como o meu trabalho está atrelado aos objetivos do desenvolvimento sustentavel. 

## Metodologia 

Descrever a minha metodologia

### Sub metodologia

Tudo aqui pertence a sessão da metodologia. 

## Aqui vou começar o meu tour de imagens  <!--{ as="img" mode="tour" }-->

### <!--{ src="assets/Screenshot 2026-11-12 at 20.26.26.png" style="background: #fff0c4;" }-->
#### Esta é uma maneira de contar a história de forma bastante visual.
Veja que aqui voce consegue escrever varias coisas 

### <!--{ src="assets/Screenshot 2026-11-12 at 22.11.37.png" style="background: #ffe7ef;" }-->
#### Esta é a minha segunda image
Aqui eu descreveria qualquer coisa que eu queira. 



## Map Tour section <!--{ as="eox-map" class="overlay-br" mode="tour" }-->
Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos. <!--{ style="opacity: 0.75; font-size: 1rem;" }-->

### <!--{ projection="globe" layers='[{"type":"Tile","properties":{"id":"osm"},"source":{"type":"OSM"}}]' center=[-47.80,-21.18] zoom="5" animationOptions="{duration:500}" }-->
#### Aqui começa o nosso tour do mapa.
Ele permite que voces modifiquem a localizacao a cada etapa, lembre que cada etapa é definido pela hashtags *h3* (*###*).

### <!--{ projection="globe" layers='[{"type":"Tile","properties":{"id":"customId"},"source":{"type":"WMTSCapabilities","url":"https://tiles.maps.eox.at/wmts/1.0.0/WMTSCapabilities.xml","layer":"s2cloudless-2024"}},{"type":"Tile","properties":{"id":"osm"},"source":{"type":"OSM"}}]' center=[-63.77,-8.76] zoom="10" animationOptions="{duration:2500}" }-->
#### Escrevo mais coisas a respeito do meu trabalho aqui.
Vejam que eu posso adicionar mais passos *h3* (*###*) heading.

#### Isso seria mais um novo passo com a mesma imagem. 
Testando esse novo passo


## Nova Etapa
To change individual parameters like zoom or center, or to change the map layers for a step, just set them using the HTML comment syntax. This changes the map setting for the current map

### Escrevo mais coisas
Tento descrever novos caminhos e explicar antes de ir para os mapas 

## Outro map tour <!--{ as="eox-map" class="overlay-br" mode="tour" }-->
Lorem ipsum dolor . <!--{ style="opacity: 0.75; font-size: 1rem;" }-->

### <!--{ layers='[{"type":"Tile","properties":{"id":"osm"},"source":{"type":"OSM"}}]' center=[-49.13,-5.50] zoom="5" animationOptions="{duration:500}" }-->
#### De novo em mais um map tour.
It allows you to have different layers, zoom and center settings for each tour "step".


### <!--{ layers='[{"type":"Tile","properties":{"id":"osm"},"source":{"type":"OSM"}},{"type":"Tile","properties":{"id":"customId"},"source":{"type":"WMTSCapabilities","url":"https://tiles.maps.eox.at/wmts/1.0.0/WMTSCapabilities.xml","layer":"s2cloudless-2025"}}]' center=[-38.51,-12.56] zoom="10" }-->
#### Movi meu mapa para salvador.
Veja como o mapa está em salvador e carregou imagens de sentinel-2 sem nuvens. 

## Elementos de Web Components
Custom elements (Web Components) can be embedded directly within markdown stories. Attributes and properties are preserved, making it easy to incorporate interactive widgets such as color legends or specialized components:

```markdown
<color-legend
  domain="[0, 100]"
  scaletype="discrete"
  range='["#eff3ff","#6baed6","#08519c", "#666666"]'
  titletext="Snowfall (mm)"
  style="--cle-background: transparent;"
></color-legend>
```

<color-legend domain="[0,100]" scaletype="discrete" range='["#eff3ff","#6baed6","#08519c", "#666666"]' titletext="Snowfall (mm)" style="--cle-background: transparent;"></color-legend>


## Encerrando

Nessa sessão, poderíamso por gráficos 