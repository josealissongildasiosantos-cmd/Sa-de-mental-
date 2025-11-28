<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Curso Premium: Ansiedade e Depressão</title>

    <!-- Fonte moderna e suave -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet" />

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.7;
            color: #2c2c2c;
            background: #fafafa;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 25px;
        }

        /* HEADER */
        header {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            padding: 3rem 0;
            text-align: center;
            border-bottom-left-radius: 60px;
            border-bottom-right-radius: 60px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.15);
        }
        header h1 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: .9;
            font-weight: 300;
        }

        /* NAV */
        nav {
            margin-top: -20px;
            background: #fff;
            padding: 1rem 0;
            border-radius: 20px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            position: sticky;
            top: 10px;
            z-index: 10;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2.5rem;
            flex-wrap: wrap;
        }
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: 0.3s;
            font-size: 1.05rem;
        }
        nav a:hover {
            color: #6a11cb;
        }

        /* HERO */
        .hero {
            text-align: center;
            padding: 5rem 0;
            background: #f4f7ff;
            border-bottom: 2px solid #eee;
        }
        .hero h2 {
            font-size: 3rem;
            font-weight: 700;
            color: #222;
        }
        .hero p {
            margin: 1.2rem auto;
            max-width: 650px;
            font-size: 1.3rem;
            color: #666;
        }
        .cta {
            margin-top: 1.5rem;
            display: inline-block;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: white;
            padding: 1rem 2.5rem;
            border-radius: 40px;
            font-size: 1.2rem;
            font-weight: 600;
            text-decoration: none;
            transition: .3s;
            box-shadow: 0 10px 20px rgba(80, 40, 200, .25);
        }
        .cta:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(80, 40, 200, .35);
        }

        /* MÓDULOS */
        .modulos {
            padding: 5rem 0;
        }
        .modulos h2 {
            text-align: center;
            font-size: 2.8rem;
            font-weight: 700;
        }
        .modulo-grid {
            margin-top: 4rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(330px, 1fr));
            gap: 2.5rem;
        }
        .modulo {
            background: white;
            border-radius: 20px;
            padding: 2.5rem;
            box-shadow: 0 10px 35px rgba(0,0,0,0.08);
            transition: 0.3s;
            border: 1px solid #eee;
        }
        .modulo:hover {
            transform: translateY(-8px);
            box-shadow: 0 18px 45px rgba(0,0,0,0.12);
        }
        .modulo h3 {
            font-size: 1.7rem;
            color: #6a11cb;
            margin-bottom: 1.2rem;
        }
        .modulo ul {
            list-style: none;
        }
        .modulo li {
            padding: 0.6rem 0;
            border-bottom: 1px solid #eee;
            font-size: 1.05rem;
        }
        .modulo li:last-child {
            border-bottom: none;
        }
        .modulo li:before {
            content: "✔ ";
            color: #2ecc71;
            font-weight: bold;
        }

        /* ALERTA */
        .alertas {
            margin: 4rem 0;
            padding: 3rem 2rem;
            text-align: center;
            color: white;
            border-radius: 25px;
            background: linear-gradient(135deg, #ff4b2b, #ff416c);
            box-shadow: 0 10px 30px rgba(255, 65, 90, 0.35);
        }
        .alertas h3 {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 1rem;
        }

        /* FOOTER */
        footer {
            background: #222;
            color: #ccc;
            padding: 2.5rem 0;
            text-align: center;
            margin-top: 5rem;
            border-top-left-radius: 50px;
            border-top-right-radius: 50px;
        }
        footer a {
            color: #9bbcff;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2.2rem; }
            .hero h2 { font-size: 2.3rem; }
            nav ul { gap: 1.2rem; }
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="container">
            <h1>🧠 Curso Premium: Ansiedade e Depressão</h1>
            <p>Aprenda, entenda e evolua com um conteúdo visual elegante, moderno e completo</p>
        </div>
    </header>

    <!-- NAV -->
    <nav>
        <ul>
            <li><a href="#modulo1">Módulo 1</a></li>
            <li><a href="#modulo2">Módulo 2</a></li>
            <li><a href="#modulo3">Módulo 3</a></li>
            <li><a href="#modulo4">Recursos</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <!-- HERO -->
    <section class="hero">
        <div class="container">
            <h2>Transforme Seu Entendimento Sobre Saúde Mental</h2>
            <p>Um curso completo com linguagem simples, visual premium e exercícios práticos para você entender e lidar melhor com ansiedade e depressão.</p>
            <a href="#modulo1" class="cta">Começar Agora (Grátis)</a>
        </div>
    </section>

    <!-- MÓDULOS -->
    <section class="modulos" id="modulo1">
        <div class="container">
            <h2>📚 Conteúdo do Curso</h2>

            <div class="modulo-grid">
                <div class="modulo" id="modulo1">
                    <h3>🌪️ Módulo 1: O que é Ansiedade?</h3>
                    <ul>
                        <li>Ansiedade normal vs. transtorno</li>
                        <li>Sintomas físicos e emocionais</li>
                        <li>Tipos de ansiedade (GAD, pânico, social)</li>
                        <li>Exemplos práticos do dia a dia</li>
                    </ul>
                </div>

                <div class="modulo" id="modulo2">
                    <h3>😔 Módulo 2: Entendendo a Depressão</h3>
                    <ul>
                        <li>Sintomas principais e critérios DSM-5</li>
                        <li>Diferença entre tristeza e depressão</li>
                        <li>Tipos (maior, persistente, bipolar)</li>
                        <li>Fatores biológicos e ambientais</li>
                    </ul>
                </div>

                <div class="modulo" id="modulo3">
                    <h3>🛠️ Módulo 3: Estratégias Práticas</h3>
                    <ul>
                        <li>Técnicas de respiração 4-7-8</li>
                        <li>Exercícios de mindfulness</li>
                        <li>Gestão do sono e rotina</li>
                        <li>Quando procurar ajuda profissional</li>
                    </ul>
                </div>

                <div class="modulo" id="modulo4">
                    <h3>📱 Módulo 4: Recursos Extras</h3>
                    <ul>
                        <li>Apps recomendados</li>
                        <li>Linhas de apoio (CVV 188)</li>
                        <li>Livros e podcasts</li>
                        <li>Certificado de conclusão</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- ALERTA -->
    <section class="alertas">
        <div class="container">
            <h3>⚠️ Atenção Importante</h3>
            <p>Este curso é educativo e não substitui atendimento profissional. Em caso de emergência emocional, ligue para o CVV (188).</p>
        </div>
    </section>

    <!-- FOOTER -->
    <footer id="contato">
        <div class="container">
            <p>&copy; 2025 Curso Ansiedade e Depressão. Design Premium.</p>
            <p>Contato: <a href="mailto:suporte@cursoansiedade.com">suporte@cursoansiedade.com</a></p>
        </div>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(link => {
            link.addEventListener('click', e => {
                e.preventDefault();
                document.querySelector(link.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
