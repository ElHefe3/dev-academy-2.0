# dev-academy-2.0
Dev Academy optimized for Core Web Vitals and SEO

# Development
- Odkomentuj 8 linię w scripts/web.js, która zwraca return true. Ma to na celu przyspieszyć development, aby zaprzestać renderowaniu pluginem wszystkich zdjęć ponownie przy każdym browser syncu.
Ten kod to: 
hexo.extend.filter.register('after_generate', function () {
-->  return true; // uncomment this line during development
  
# Styles
- Style dodajemy zgodnie z mobile first. Najpierw stylujemy od 360 przesuwając sie ku górze. Stylowanie po innych breakpointach powyżej 767px odbywa się w pliku css/desktop.scss, który dołączony jest do strony w momencie kiedy rozdzielczość urządzenia ma min 768px.
- Każda nowa sekcja, czy komponent to powinien być nowy plik w .scss, aby zachować spójność, czytelność i porządek kodu.
