# NewsAnalyzer 
____

## Автор - Сергей Лысанов
http://seregabb.github.io

____

Данный проект - выпускная работа Яндекс.Практикума, выполняемая студентом. Его цель - показать, насколько были усвоены полученные знания и умения, а также способность самостоятельно изучить технологии, которые не были даны в процессе обучения. 
В данном проекте были использованы такие технологии как HTML, CSS, Java Script, Webpack.

____

На данном этапе реализована только вёрстка основных блоков и страниц (пока что без адаптива). 
После проверки ревьювером, будет дописан адаптив. А также следующим этапом будет реализация JS.

P.s. на главной странице блоки с прелоадером и блок "нет результатов" скрыты. Чтобы увидеть их, нужно в консоли по очереди ввести команды: 
```js
    document.querySelector('.no-result').classList.toggle('section_visibility-hidden');
```
и 
```js
    document.querySelector('.loading').classList.toggle('section_visibility-hidden');
```
