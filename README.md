<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Minha Loja Online</h1>
        <nav>
            <a href="#">Início</a>
            <a href="#">Produtos</a>
            <a href="#">Contato</a>
        </nav>
    </header>
    <main>
        <section id="produtos">
            <article>
                <h2>Produto 1</h2>
                <p>Descrição do Produto 1.</p>
                <p>Preço: R$100</p>
            </article>
            <!-- Adicione mais produtos aqui -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Minha Loja Online</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
header nav a {
    color: #fff;
    margin: 0 15px;
    text-decoration: none;
}
main {
    padding: 20px;
}
section#produtos article {
    border: 1px solid #ddd;
    padding: 15px;
    margin-bottom: 10px;
}
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
