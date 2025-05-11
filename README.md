# Ex02 Django ORM Web Application
## Date: 21.04.2025

## AIM
To develop a Django application to store and retrieve data from Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM
![image](https://github.com/user-attachments/assets/15285c0d-85a1-4616-9b52-9dfcede7a99f)



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Movie Database</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f0f0f0; padding: 20px; }
        h1 { text-align: center; }
        table {
            width: 80%;
            margin: auto;
            border-collapse: collapse;
            background: white;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>

<h1>Movies Database</h1>

<table>
    <tr>
        <th>Title</th>
        <th>Genre</th>
        <th>Release Year</th>
        <th>Rating</th>
        <th>Director</th>
    </tr>
    {% for movie in movies %}
    <tr>
        <td> Movie.title </td>
        <td> Movie.genre </td>
        <td> Movie.release_year </td>
        <td> Movie.rating </td>
        <td> Movie.director </td>
    </tr>
    {% endfor %}
</table>

</body>
</html>
```

## OUTPUT
![433012990-d7ec431a-37ca-413c-91c3-249169bd45c0](https://github.com/user-attachments/assets/36ef4cfc-1dc2-4a6f-88df-02551747d3fd)

Include the screenshot of your admin page.


## RESULT
Thus the program for creating a database using ORM hass been executed successfully
