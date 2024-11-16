# Plataforma-financeira-
Vigilante_octo-gingando
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plataforma Financeira</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Plataforma de Investimentos</h1>
        <nav>
            <a href="#depositos">Depósitos</a>
            <a href="#saques">Saques</a>
            <a href="#investimentos">Investimentos</a>
            <a href="#usuarios">Usuários</a>
        </nav>
    </header>
    <main>
        <section id="dashboard">
            <h2>Bem-vindo!</h2>
            <p>Total de usuários: <span id="total-usuarios">0</span></p>
            <p>Rendimentos diários: <span id="rendimentos-diarios">$0</span></p>
        </section>

        <section id="depositos">
            <h2>Depósitos</h2>
            <form id="deposit-form">
                <input type="number" placeholder="Valor do Depósito" required>
                <button type="submit">Depositar</button>
            </form>
            <h3>Histórico de Depósitos</h3>
            <ul id="deposit-history"></ul>
        </section>

        <section id="saques">
            <h2>Saques</h2>
            <form id="withdraw-form">
                <input type="number" placeholder="Valor do Saque" required>
                <button type="submit">Solicitar Saque</button>
            </form>
            <h3>Histórico de Saques</h3>
            <ul id="withdraw-history"></ul>
        </section>

        <section id="investimentos">
            <h2>Investimentos</h2>
            <div class="investment">
                <h3>Plano 1</h3>
                <p>Rendimento: 5% ao dia</p>
            </div>
            <div class="investment">
                <h3>Plano 2</h3>
                <p>Rendimento: 7% ao dia</p>
            </div>
            <div class="investment">
                <h3>Plano 3</h3>
                <p>Rendimento: 10% ao dia</p>
            </div>
        </section>

        <section id="usuarios">
            <h2>Usuários</h2>
            <ul id="user-list"></ul>
        </section>
    </main>
    <script src="scripts.js"></script>
</body>
</html>
