<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css"
        integrity="sha256-h20CPZ0QyXlBuAw7A+KluUYx/3pK+c7lYEpqLTlxjYQ=" crossorigin="anonymous" />
    <title>todo List</title>
</head>

<body>
    <header>
        <h2>Todo List</h2>
    </header>
    <!--For adding Tasks-->
    <div id="main">
        <textarea id="taskTitle" rows="1" cols="100" placeholder="Enter Title"> </textarea>
        <textarea id="taskDesc" rows="4" cols="100" placeholder="Enter Task Description"> </textarea>
        <button id="add-btn">Add</button>


    </div>
    <aside class='display'>
        <!--All Stored Tasks-->

    </aside>




    <script type="text/javascript" src="app.js"> </script>
</body>

</html>
