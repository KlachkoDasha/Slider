# Slider
Для того, чтобы создать слайдер, необходимо указать несколько свойств.

# Description
Свойство **slide** определяет каждый отдельный слайд.<br>
Свойство **nextArrow** хранит данные о стрелке для перехода на следующий слайд.<br>
Свойство **prevArrow** хранит данные о стрелке для возврата к предыдущему слайду.<br>
Свойство **totalCounter** хранит данные о количестве слайдов.<br>
Свойство **currentCounter** хранит данные о текущем слайде.<br><br>

# Installation
Подключить этот модуль можно импортировав его в главный файл и указав адрес до него. Например:<br>

<code>import slider from './modules/slider';</code>

А далее вызвать эту функцию и указать свои данные. Например:<br>
<pre>
<code>
slider({<br>
   slide: '.offer__slide',<br>
   nextArrow: '.offer__slider-next', <br>
   prevArrow: '.offer__slider-prev',<br>
   totalCounter: '#total',<br>
   currentCounter: '#current'<br>
});
</code>
</pre>
