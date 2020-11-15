# Научиться учиться
------------------------------------------------------------
## Проект создан для оттачивания навыков верстки HTML и CSS.
 
 В основе проекта содержится структурированный и семантически корректный код с использованием семантических тэгов **header, main, section, footer, nav**. 
 Код написан по правилам **методологии БЭМ**. Файлы и пути к файлам в проекте также организованы по **БЭМ Nasted**.
 
Данный проект был дополнен новыми секциями с элементами *анимации* и *видео-контента*. 
 
При создании анимации был задействован **кейфрейм** и трансформация **rotate** для поворота объекта на 360 градусов с бесконечным движением. Чтобы не допустить переполнение родительского блока для данной анимации, было использовано свойство overflow. 
 
Для всех ссылок также используется анимация - при наведении мыши такст ссылок становится прозрачным. Для этого также был использован **кейфрейм** и свойство **opacity** c псевдоклассом **:hover**: 

    ```css
    @keyframes opacity { 
      from { 
        opacity: 1; 
      } 
      to { 
        opacity: 0.4; 
      } 
    } 

      .header__link:hover {
        animation: opacity 1.2s ease-in forwards;
      } 
    ``` 
    
Для вставки видео был использван *API YouTube*.






  
