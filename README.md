# Titulo del proyecto

## Inpiracion del proyecto & objetivo

-  ejercicio de programacion en  JavaScript

## Tecnologias usadas

- Ide
    <!-- visual studio code -->
    <code><img height="25" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"></code>

- Programas usados
    <!-- figma -->
    <code><img height="30" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"></code>
- lenguajes/frameworks usados
    <!-- bootstrap -->
    <code><img height="30" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></code><!-- css -->
    <code><img height="30" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></code><!-- javascript -->
    <code><img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"></img></code>
## Vista previa del proyecto

<img src="pr-progres/project-preview.gif" aling="center" ></img>

## Estado del proyecto

|Trabajando en el proyecto|✔️|
| -------------------------- | :----------------: |
|            Web responsive  |      ❌        |
|           Hosting          |    |
| Websever app online        |         ❌    |  
| Dispone de trello          |         ❌    |  
<details open>
<summary>⚙️ documentacion del proyecto ⚙️</summary>

1. Se introducen los datos
   ```js
           function temp() {
            // 1. obten el valor del input
            input = window.prompt("Ingrese la temperatura");
        }
   ```
2. Se procesas el valor del input y se cambia la imagen de la temperatura
   ```js
            if (input <= 15) {
                document.getElementById("temp-image").src = "img/cold.png";
                console.log("frio");
            }
            if (input > 15) {
                document.getElementById("temp-image").src = "img/good.png";
                console.log("bien");

            }
            if (input >= 30) {
                document.getElementById("temp-image").src = "img/hot.png";
                console.log("calor");
            }
   ```
3. Se muestra el resultado
   ```js
        function temp() {
            // 1. obten el valor del input
            input = window.prompt("Ingrese la temperatura");
            // 3. imprime el valor en el output
            document.getElementById("temp-output").value = input;
        }
   ```

</details>

<!-- └── / ├── │ -->


## Licencia

``no disponible``
