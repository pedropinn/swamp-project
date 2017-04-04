## Web Performance

O projeto tem foco em desempenho. As pontuações medianas do Web Page Test têm um [Índice de Velocidade](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index) de ~ 1100 (1000 é ideal) e um Índice de Velocidade de repetição-visita de ~ 550 graças a Preenchimento de Service worker e cache.


## Créditos

Tomei como ponto de partida um projeto do [Google(Web Starter Kit)](https://developers.google.com/web/tools/starter-kit/)  para iniciantes onde o foco é o mesmo deste projeto, um pouco mais simples mas com a mesma ideia.

Também usarei as bibliotécas core do projeto do Google, e outras bibliotecas de terceiros conforme eu achar interessante. Logo à baixo eu listarei as principais bibliotecas utilizadas, provavelmente estarão todas num package.json e/ou em um bower.json então não se preocupe com esta lista.

* [Service Worker Precache (sw-precache)](https://github.com/GoogleChrome/sw-precache/)
* [Service Worker Toolbox (sw-toolbox)](https://github.com/GoogleChrome/sw-toolbox/)
* [Google Analytics off-line (sw-offline-google-analytics)](https://github.com/GoogleChrome/sw-helpers/tree/master/packages/sw-offline-google-analytics)
* [Service Worker helper libraries (sw-helpers)](https://github.com/GoogleChrome/sw-helpers)  

## Browser Support

Pretendo oficialmente dar suporte as últimas versões dos seguintes navegadores:

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 9+


Isto não quer dizer que o projeto não pode ser usado em navegadores mais antigos do que aqueles refletidos, mas meramente que nosso foco será em garantir que nossos layouts funcionem bem nos acima.

## License

MIT  
Copyright 2017 Charles Araújo da Silva
