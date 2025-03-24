<!-- contact.html -->
<!DOCTYPE html>
<html>
<head>
    <title>Contato - Leatrix</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .contact-form {
            max-width: 600px;
            margin: 50px auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <form class="contact-form" action="https://formspree.io/f/mqapbedo" method="POST">
            <h2>Fale Conosco</h2>
            
            <div class="mb-3">
                <label class="form-label">Nome:</label>
                <input type="text" name="name" class="form-control" required>
            </div>

            <div class="mb-3">
                <label class="form-label">Email:</label>
                <input type="email" name="_replyto" class="form-control" required>
            </div>

            <div class="mb-3">
                <label class="form-label">Mensagem:</label>
                <textarea name="message" class="form-control" rows="5" required></textarea>
            </div>

            <input type="hidden" name="_subject" value="Solicita deletar conta">
            
            <button type="submit" class="btn btn-primary">Deletar minha conta</button>
        </form>
    </div>
</body>
</html>
