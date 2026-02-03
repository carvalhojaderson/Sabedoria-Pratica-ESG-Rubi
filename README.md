<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundo Sabedoria Prática ESG</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Estilos inline para garantir que funcione -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
            color: #ffffff;
            min-height: 100vh;
        }
        
        .ruby-gradient {
            background: linear-gradient(135deg, #DC143C 0%, #8B0000 100%);
        }
        
        .hero-section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            background: radial-gradient(circle at center, rgba(220, 20, 60, 0.1) 0%, transparent 70%);
        }
        
        .content-section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .card {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(220, 20, 60, 0.3);
            border-radius: 1rem;
            padding: 2rem;
            margin: 1rem 0;
            backdrop-filter: blur(10px);
        }
        
        .btn-primary {
            background: linear-gradient(135deg, #DC143C 0%, #8B0000 100%);
            color: white;
            padding: 1rem 2rem;
            border-radius: 2rem;
            border: none;
            cursor: pointer;
            font-weight: bold;
            transition: transform 0.3s;
            display: inline-block;
            text-decoration: none;
            margin: 0.5rem;
        }
        
        .btn-primary:hover {
            transform: scale(1.05);
        }
        
        .btn-secondary {
            border: 2px solid #DC143C;
            color: #DC143C;
            padding: 1rem 2rem;
            border-radius: 2rem;
            background: transparent;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s;
            display: inline-block;
            text-decoration: none;
            margin: 0.5rem;
        }
        
        .btn-secondary:hover {
            background: #DC143C;
            color: white;
        }
        
        h1, h2, h3 {
            font-family: 'Georgia', serif;
        }
        
        .ruby-icon {
            width: 80px;
            height: 80px;
            margin-bottom: 2rem;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.8; }
        }
        
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-width: 600px;
            margin: 0 auto;
        }
        
        input, textarea, select {
            padding: 1rem;
            border-radius: 0.5rem;
            border: 1px solid rgba(220, 20, 60, 0.3);
            background: rgba(0, 0, 0, 0.3);
            color: white;
            font-size: 1rem;
        }
        
        input::placeholder, textarea::placeholder {
            color: #888;
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            border-top: 1px solid rgba(220, 20, 60, 0.2);
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero-section">
        <svg class="ruby-icon" viewBox="0 0 24 24" fill="#DC143C">
            <path d="M12 2L4 9l8 13 8-13-8-7zm0 2.5L17.5 9 12 17.5 6.5 9 12 4.5z"/>
        </svg>
        
        <h1 style="font-size: 3rem; margin-bottom: 1rem; background: linear-gradient(135deg, #ff6b6b, #DC143C); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
            Mais valioso que rubis
        </h1>
        
        <p style="font-size: 1.5rem; color: #ccc; margin-bottom: 2rem;">
            Transforme imposto em legado sustentável
        </p>
        
        <p style="max-width: 600px; color: #aaa; margin-bottom: 2rem; line-height: 1.6;">
            Plataforma de facilitação para empresas, bancos e fundos tributários 
            redirecionarem IRPJ devido para projetos de restauração social e 
            territórios culturais permanentes.
        </p>
        
        <div>
            <a href="#cadastro" class="btn-primary">Cadastrar Projeto</a>
            <a href="#apoiar" class="btn-secondary">Quero Apoiar</a>
        </div>
    </section>

    <!-- Mecanismos -->
    <section class="content-section">
        <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 1rem;">Mecanismo de Transformação</h2>
        <p style="text-align: center; color: #aaa; margin-bottom: 3rem;">Imposto em Impacto</p>
        
        <div class="grid-3">
            <div class="card">
                <h3 style="color: #DC143C; margin-bottom: 1rem;">🎯 Lei de Incentivo ao Esporte</h3>
                <p style="color: #ccc;">Destinação direta via legislação vigente, transformando obrigação tributária em investimento social.</p>
            </div>
            
            <div class="card">
                <h3 style="color: #DC143C; margin-bottom: 1rem;">👶 FIA</h3>
                <p style="color: #ccc;">Fundo da Infância e Adolescência para projetos de proteção e desenvolvimento de jovens.</p>
            </div>
            
            <div class="card">
                <h3 style="color: #DC143C; margin-bottom: 1rem;">🎨 Incentivo à Cultura</h3>
                <p style="color: #ccc;">Rouanet e outras leis para territórios culturais permanentes e produção artística.</p>
            </div>
        </div>
    </section>

    <!-- Cadastro -->
    <section id="cadastro" class="content-section">
        <div class="card">
            <h2 style="text-align: center; font-size: 2rem; margin-bottom: 0.5rem;">Cadastre seu Projeto</h2>
            <p style="text-align: center; color: #aaa; margin-bottom: 2rem;">Tem uma iniciativa de impacto social?</p>
            
            <form onsubmit="event.preventDefault(); alert('Projeto cadastrado com sucesso!');">
                <input type="text" placeholder="Nome do Projeto" required>
                <input type="text" placeholder="Responsável" required>
                <input type="email" placeholder="Email" required>
                <select required style="color: #888;">
                    <option value="">Tipo de Projeto</option>
                    <option value="cultural">Território Cultural</option>
                    <option value="esporte">Projeto Esportivo</option>
                    <option value="educacao">Educação</option>
                </select>
                <textarea rows="4" placeholder="Descrição do impacto social..." required></textarea>
                <button type="submit" class="btn-primary" style="width: 100%;">Enviar Cadastro</button>
            </form>
        </div>
    </section>

    <!-- Apoiar -->
    <section id="apoiar" class="content-section">
        <div class="card">
            <h2 style="text-align: center; font-size: 2rem; margin-bottom: 0.5rem;">Seja um Apoiador</h2>
            <p style="text-align: center; color: #aaa; margin-bottom: 2rem;">Empresas podem destinar IRPJ sem custo extra</p>
            
            <div style="text-align: center; padding: 2rem; background: rgba(220, 20, 60, 0.1); border-radius: 1rem;">
                <p style="font-size: 3rem; color: #DC143C; font-weight: bold;">6%</p>
                <p style="color: #ccc;">do IRPJ devido pode ser destinado</p>
                <br>
                <a href="mailto:contato@sabedoriapratica.org" class="btn-primary">Falar com Consultor</a>
            </div>
        </div>
    </section>

    <!-- Citação -->
    <section class="content-section" style="text-align: center;">
        <p style="font-size: 1.5rem; font-style: italic; color: #DC143C; max-width: 600px; margin: 0 auto;">
            "Mais preciosa é do que os rubis, e tudo o que mais possas desejar não se pode comparar a ela."
        </p>
        <p style="color: #888; margin-top: 1rem;">— Provérbios 31</p>
    </section>

    <footer>
        <p style="color: #666;">© 2026 Fundo Sabedoria Prática ESG</p>
        <p style="color: #444; font-size: 0.9rem; margin-top: 0.5rem;">Mais valioso que rubis</p>
    </footer>

    <!-- JavaScript simples e seguro -->
    <script>
        // Smooth scroll para links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });
        
        console.log('Fundo Sabedoria Prática ESG - Site carregado com sucesso!');
    </script>

</body>
</html>
