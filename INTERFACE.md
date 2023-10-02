# Interface to php from javascript

There are two `HTML` files that has accompanying `js` files that function to access the `php` files on the server to interface with the database from the user end.

You should not need to change anything from the templates, but if you edit form names or the id of the viewer in the `html` files, make sure they are also changed on the `js` files.

The namse are located on `line 1` for both the [js/form.js](template/js/form.js) and the [js/view.js](template/js/view.js) files.

![Alt text](<img/Screenshot 2023-10-01 at 9.26.20 PM.jpg>)
![Alt text](<img/Screenshot 2023-10-01 at 9.16.04 PM.jpg>)
![Alt text](<img/Screenshot 2023-10-01 at 9.26.31 PM.jpg>)
![Alt text](<img/Screenshot 2023-10-01 at 9.16.14 PM.jpg>)

The `js` files use the [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) to request data from an API or send data via [FormData](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#body).

**Note:** If you want to see more how endpoints work, visit [https://sampleapis.com/](https://sampleapis.com/).
