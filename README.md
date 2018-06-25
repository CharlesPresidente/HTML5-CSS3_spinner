# HTML5/CSS3 - Spinner

Elemento Spinner 100% CSS, indicador de carregamento ou regarregamento de conteúdo.


## Arquivos

### .html

	<!DOCTYPE html>
    <html lang="pt">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Document</title>
    </head>

    <body>
        <div class="spinner"></div>
    </body>

    </html>

### .css
Destaque para os elementos sinalizados com as setas:

	<style type="text/css">
        body {
            margin: 0;
            padding: 0;
            background-color: #0b0b0b;
        }
        .spinner {
            margin: 15em auto;
            border: 16px solid #e3e3e3;
            border-radius: 50%;
            border-top: 16px solid #3498db;
            width: 150px;
            height: 150px;
            animation: spin 1s linear infinite; <--
        }
        @keyframes spin {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }
    </style>
