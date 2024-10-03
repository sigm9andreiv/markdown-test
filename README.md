# Введение в веб-разработку   
>"Программирование - это не просто наука, это искусство." - Неизвестный автор
---
## **План обучения**  
1. Изучить основы HTML  
2. Изучить основы CSS  
3. Изучить основы JavaScript  
---
 ### **Основные технологии**  
- HTML  
- CSS  
- JavaScript
---
 ### **HTML**  
 
  ***HTML (HyperText Markup Language) - это стандартный язык разметки для создания вебстраниц. Он используется для структурирования контента на веб-странице.***  
### **CSS**  
 ***CSS (Cascading Style Sheets) - это язык стилей, используемый для описания внешнего 
вида документа, написанного на HTML. С его помощью можно задавать цвета, шрифты, 
отступы и другие визуальные параметры***
### **JavaScript**  
***JavaScript - это язык программирования, который позволяет реализовывать сложное 
поведение на веб-страницах. Он используется для создания интерактивных элементов, 
таких как кнопки, формы и анимации***  
### **Пример кода**  
### **HTML**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Пример HTML</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <div class="container">
 <h1>Добро пожаловать на мой сайт</h1>
 <p>Это пример веб-страницы, созданной с использованием HTML и CSS.</p>
 <button onclick="showMessage()">Нажми меня</button>
 </div>
 <script src="script.js"></script>
</body>
</html>
```
### **CSS**  
```CSS
body {
 font-family: Arial, sans-serif;
 background-color: #f0f0f0;
 margin: 0;
 padding: 0;
}
.container {
 max-width: 800px;
 margin: 0 auto;
 padding: 20px;
 background-color: #fff;
 box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
h1 {
 color: #333;
}
p {
 font-size: 1.2em;
 line-height: 1.6;
}
button {
 padding: 10px 20px;
 font-size: 1em;
 color: #fff;
 background-color: #007bff;
 border: none;
 border-radius: 5px;
 cursor: pointer;
}
button:hover {
 background-color: #0056b3;
}```
 ### **JavaScript**
```JavaScript
function showMessage() {
 alert('Привет, мир!');
 console.log('Кнопка нажата');
}
document.addEventListener('DOMContentLoaded', function() {
 console.log('Страница загружена');
});```

  
