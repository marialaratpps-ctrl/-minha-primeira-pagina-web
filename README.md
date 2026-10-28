<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha página pessoal</title>
</head>
<body>

    <h1>Minha página pessoal</h1>

    <p>Seja bem-vindo à minha página!</p>

    <h2>Sobre mim</h2>
    <p>Meu nome é Maria Lara Tavares de Paula.</p>

    <h2>Contato</h2>
    <p>
        E-mail:
        <a href="mailto:marialaratpps@gmail.com">
            marialaratpps@gmail.com
        </a>
    </p>

    <hr>

    <h2>Entre em contato</h2>

    <form action="#" method="get">
        <fieldset>
            <legend>Formulário de contato</legend>

            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome" required>
            <br><br>

            <label for="email">E-mail:</label><br>
            <input type="email" id="email" name="email" required>
            <br><br>

            <label for="assunto">Assunto:</label><br>
            <input type="text" id="assunto" name="assunto" required>
            <br><br>

            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem" rows="5" cols="30" required></textarea>
            <br><br>

            <button type="submit">Enviar</button>
            <button type="reset">Limpar</button>
        </fieldset>
    </form>

</body>
</html>
