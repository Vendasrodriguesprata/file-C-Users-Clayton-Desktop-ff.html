<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato via WhatsApp</title>
</head>
<body>
    <h1>Contate-nos via WhatsApp</h1>
    <button onclick="abrirWhatsApp()">Clique aqui para enviar uma mensagem</button>

    <script>
        function abrirWhatsApp() {
            // Array com os números de telefone
            const whatsappNumbers = [
                "https://wa.me/5516982113338",
                "https://wa.me/5516981092293"
            ];

            // Selecionar aleatoriamente um número
            const randomIndex = Math.floor(Math.random() * whatsappNumbers.length);
            window.location.href = whatsappNumbers[randomIndex];
        }
    </script>
</body>
</html>
