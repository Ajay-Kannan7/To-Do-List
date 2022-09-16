# To-Do-List
This is a to-do list CRUD application built using HTML, CSS, Javascript.
## What I learnt
 ### 1) How to use Javscript DOM to dynamically render new element onto the screen as a response using event listeners.
We'll create the element like this:
```
  var nodeTodo=document.createElement('div'); // This will create a <div></div> element
  var appendNode=document.querySelector('.to-do-task'); // We'll select the node within which we'll render the element
  nodeTodo.innerHTML=
    `
        <div>
            <h3>${todoContent}</h3>
        </div>
        <button class="remove-button">Done</button>
    `
    appendNode.append(nodeTodo);  // We'll append that created node with content and it'll be rendered
```
 ### 2) Usage of the event object
 
 Event is an object that gets returned after an event such as a click, change, mouseover event has been triggered and we can 
 us that object to select the element at that event and work with it, like this:
```
     var removeNode=event.target;
```
## Desktop Design
<img width="947" alt="image" src="https://user-images.githubusercontent.com/78952955/175110950-5f4d271e-4d1b-406d-b140-7677d596b295.png">

## Mobile Design
![image](https://user-images.githubusercontent.com/78952955/175111113-99a18e2d-a04a-4905-9d7a-5bb7cd6a046a.png)

## Live URL
https://todo-task-web.netlify.app/
