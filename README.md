# List
This is my fourth project for training purposes - YouCode. This page is in polish language. 
## About this project
"List" is page that allows you to create any list. You can enter there whatever you want and then mark done task or remove a completed/useless task.
Most of my code is using JS. This is snippet of my code: ``` 
    const render = () => {
        let tasksListHTMLContent = "";
        for (const task of tasks) {
            tasksListHTMLContent += `
        <li class="tasks__item js-task">
        <button class="tasks__button tasks button--toggleDone js-toggleDone">
        ${task.done ? "✔" : ""}</button>
        <span class= "tasks__content ${task.done ? "tasks__content--done" : ""}">${task.content}</span>
        <button class="tasks__button tasks__button--remove js-remove">🗑</button>
        </li>
        `;
        }
        document.querySelector(".js-tasks").innerHTML = tasksListHTMLContent;
        bindEvents();
    };```
    Visit my demo and have a good time. I greet you.

https://user-images.githubusercontent.com/99915297/157556166-8dd44184-98de-4954-a759-8bb49eff5bf6.mp4


    
## Languages
HTML, CSS. JS, GRID.
### demo
https://monikas1989.github.io/List/
