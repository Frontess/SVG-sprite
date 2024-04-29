## Пример использования SVG-спрайтов

<img width="1387" alt="Снимок экрана 2024-04-29 в 18 05 49" src="https://github.com/Frontess/SVG-sprite/assets/127450758/a38a79dd-b1d7-41a7-b70d-560f80044f11">


:large_orange_diamond: SVG-спрайты используются для улучшения производительности сайта, управления графикой и стилизации иконок с помощью CSS.

:large_orange_diamond: Оформление кода для использования SVG на сайте:

```

<svg class="icon" width="550" height="320" viewBox="0 0 550 275">
  <use xlink:href="sprite.svg#Frame 1"></use>
</svg>

```
Оптимизация спрайт-сетами всё ещё актуальна, даже после апгрейда HTTP/1.1 на протокол HTTP/2. 
Если HTTP/2 оптимизирует использование сети, это не станет основанием для полного отказа от фронт-энд оптимизаций, среди которых спрайт-сеты, CSS/JS минификации и бандлы.

:large_orange_diamond: Плюсы: 
- Использование SVG улучшает улучшает производительность сайта за счет сокращения количества HTTP-запросов.
- Сохранение качества изображений, иконок при адаптиве.
- Широкие возможости творчества и стилизации иконок, в коде есть пример стилизации [мордочки панды](https://codepen.io/marina-frontend/pen/GRLLKBQ)

***



<div id="footer" align="center">

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGptcXV4NzhmbmVvMWFiaTh2OGJ6bjg2ZnZscXE1d3I3dHVkZ24wNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5D4orIAAOJOHyp8rs9/giphy.gif" width="200" />

  
</div>
