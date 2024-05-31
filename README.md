<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Livros</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }
        .category {
            background-color: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .category h2 {
            text-align: center;
            color: #333;
        }
        .books {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .book {
            margin: 10px;
            text-align: center;
            flex: 1 1 calc(30% - 40px);
            box-sizing: border-box;
        }
        .book img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            transition: transform 0.2s;
        }
        .book img:hover {
            transform: scale(1.05);
        }
        .book-title {
            margin: 10px 0;
            font-size: 1.1em;
            font-weight: bold;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="category">
            <h2>Livros de 2023</h2>
            <div class="books">
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_1" alt="Livro 1">
                    <div class="book-title">Título do Livro 1</div>
                </div>
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_2" alt="Livro 2">
                    <div class="book-title">Título do Livro 2</div>
                </div>
                <!-- Adicione mais livros conforme necessário -->
            </div>
        </div>
        <div class="category">
            <h2>Livros Infantis</h2>
            <div class="books">
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_3" alt="Livro Infantil 1">
                    <div class="book-title">Título do Livro Infantil 1</div>
                </div>
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_4" alt="Livro Infantil 2">
                    <div class="book-title">Título do Livro Infantil 2</div>
                </div>
                <!-- Adicione mais livros conforme necessário -->
            </div>
        </div>
        <div class="category">
            <h2>Livros Didáticos</h2>
            <div class="books">
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_5" alt="Livro Didático 1">
                    <div class="book-title">Título do Livro Didático 1</div>
                </div>
                <div class="book">
                    <img src="URL_DA_IMAGEM_DO_LIVRO_6" alt="Livro Didático 2">
                    <div class="book-title">Título do Livro Didático 2</div>
                </div>
                <!-- Adicione mais livros conforme necessário -->
            </div>
        </div>
    </div>
</body>
</html>
