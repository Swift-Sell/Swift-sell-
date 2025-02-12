body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #1E3A8A;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.btn {
    background-color: #F97316;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background-color: #1E3A8A;
    color: white;
}

.hero h1 {
    font-size: 36px;
}

.services {
    text-align: center;
    padding: 50px 20px;
}

.service-box {
    background: white;
    padding: 20px;
    margin: 20px auto;
    max-width: 400px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #1E3A8A;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">Meu Site</div>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#valores">Nossos Valores</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <h1>Bem-vindo ao Meu Site</h1>
        <p>Oferecemos as melhores soluções para você.</p>
    </section>

    <section id="valores" class="info-section">
        <h2>Nossos Valores</h2>
        <p>Compromisso, inovação e qualidade no atendimento ao cliente.</p>
    </section>

    <section id="servicos" class="services">
        <h2>Nossos Serviços</h2>
        <div class="service-box">
            <h3>Serviço 1</h3>
            <p>Descrição do serviço 1.</p>
        </div>
        <div class="service-box">
            <h3>Serviço 2</h3>
            <p>Descrição do serviço 2.</p>
        </div>
    </section>

    <section id="contato" class="info-section">
        <h2>Contato</h2>
        <p><strong>Email:</strong> <a href="mailto:alexcruz199905@gmail.com">alexcruz199905@gmail.com</a></p>
        <p><strong>Telefone:</strong> <a href="tel:+950893363">950 893 363</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
