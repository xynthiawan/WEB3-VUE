# WEB3-VUE

link: https://xynthiawan.github.io/WEB3-VUE/

last change: 

A. "Uncaught TypeError: Vue is not a constructor" indicates that Vue is not defined or not properly loaded in my web page. Installed Vue through NPM.included the Vue library in my HTML file before my own JavaScript code. I included the Vue library by adding `<script src="https://unpkg.com/vue@3"></script>`

B. actually creating a Vue instance. To create a Vue instance, I called the createApp method of the Vue object and store the result in a variable. Then, I mounted the instance to a specific element using the mount method.

C. update the "removeTodo" method in the Vue instance. Currently, it's looping through the list of to-do items and trying to find the item with the matching id. But, it's not removing the item correctly, and that's why the "Remove" button is not working.

