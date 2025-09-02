<!DOCTYPE html>
<html>
  <head>
  <title>Павел Петров</title><meta charset="utf-8">
 </head>
 <body>
 
    <h4>ivanov</h4>
    <input type="number" value="5" id="n1">
    <input type="number" value="15" id="n2">
    <input type="number" value="" id="result">
    <button id="bt" onclick="
                                 
      // строка ниже сработает если в title вы напишете свой логин
      // document.querySelector('h4').textContent = document.title;
     
      /* извлечение данных */  
      const n1 = Number(document.querySelector('#n1').value);
      const n2 = Number(document.querySelector('#n2').value); 
       
      
      /* вычисления  */                       
      const result = n1 * n2;
                             
       
       
       
      /* запись результата */ 
      document.querySelector('#result').value = result;                                                          
    ">Выполнить задание</button>
   
  
 
 
</body>
</html>
