<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GUILHERME-TCH | Gestor de Biblioteca</title>
    <link rel="stylesheet" href="https://cloudflare.com">
    <style>
        :root { --primary: #2563eb; --accent: #d946ef; --bg: #f1f5f9; --card: #ffffff; --text: #1e293b; }
        .dark-mode { --bg: #0f172a; --card: #1e293b; --text: #f1f5f9; }
        
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background: var(--bg); color: var(--text); transition: 0.3s; padding-bottom: 50px; }

        header { background: #1e293b; padding: 1rem 5%; color: white; display: flex; justify-content: space-between; align-items: center; }
        
        /* Formulário de Cadastro */
        .admin-panel { background: var(--card); margin: 20px 5%; padding: 20px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .admin-panel h2 { margin-bottom: 15px; font-size: 1.2rem; }
        .input-group { display: flex; gap: 10px; flex-wrap: wrap; }
        input, select { padding: 10px; border: 1px solid #ddd; border-radius: 8px; flex: 1; min-width: 150px; }
        .btn-add { background: var(--accent); color: white; border: none; padding: 10px 20px; border-radius: 8px; cursor: pointer; font-weight: bold; }

        .container { padding: 20px 5%; }
        .grid-livros { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 20px; }
        
        .card-livro { background: var(--card); padding: 20px; border-radius: 15px; text-align: center; animation: fadeIn 0.5s; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        .capa { height: 120px; width: 90px; margin: 0 auto 15px; border-radius: 5px; display: flex; align-items: center; justify-content: center; color: white; font-size: 2.5rem; box-shadow: 3px 3px 8px rgba(0,0,0,0.2); }
        .btn-del { background: #ff4444; color: white; border: none; padding: 5px 10px; border-radius: 5px; margin-top: 10px; cursor: pointer; font-size: 0.8rem; }
        
        #theme-btn { background: none; border: 1px solid white; color: white; cursor: pointer; padding: 5px 10px; border-radius: 5px; }
    </style>
</head>
<body>

<header>
    <div class="logo"><b>GUILHERME-TCH</b></div>
    <button id="theme-btn" onclick="document.body.classList.toggle('dark-mode')">Mudar Tema</button>
</header>

<section class="admin-panel">
    <h2><i class="fas fa-plus-circle"></i> Adicionar Novo Livro</h2>
    <div class="input-group">
        <input type="text" id="novo-titulo" placeholder="Nome da Matéria (ex: Química)">
        <select id="novo-icone">
            <option value="fa-book">Livro Padrão</option>
            <option value="fa-flask">Ciências/Química</option>
            <option value="fa-calculator">Cálculo</option>
            <option value="fa-atlas">Geografia</option>
            <option value="fa-palette">Artes</option>
            <option value="fa-dumbbell">Ed. Física</option>
        </select>
        <input type="color" id="nova-cor" value="#2563eb" title="Escolha a cor da capa">
        <button class="btn-add" onclick="adicionarLivro()">Adicionar à Estante</button>
    </div>
</section>

<div class="container">
    <div class="grid-livros" id="estante">
        <!-- Livros iniciais -->
    </div>
</div>

<script>
    // Lista inicial de livros
    let livros = [
        { titulo: 'Matemática', icone: 'fa-calculator', cor: '#ef4444' },
        { titulo: 'Português', icone: 'fa-language', cor: '#3b82f6' },
        { titulo: 'Filosofia', icone: 'fa-brain', cor: '#8b5cf6' }
    ];

    function renderizarEstante() {
        const estante = document.getElementById('estante');
        estante.innerHTML = '';
        
        livros.forEach((livro, index) => {
            estante.innerHTML += `
                <div class="card-livro">
                    <div class="capa" style="background: ${livro.cor}"><i class="fas ${livro.icone}"></i></div>
                    <h3>${livro.titulo}</h3>
                    <button class="btn-del" onclick="removerLivro(${index})">Excluir</button>
                </div>
            `;
        });
    }

    function adicionarLivro() {
        const titulo = document.getElementById('novo-titulo').value;
        const icone = document.getElementById('novo-icone').value;
        const cor = document.getElementById('nova-cor').value;

        if (titulo === '') return alert("Digite o nome do livro!");

        livros.push({ titulo, icone, cor });
        document.getElementById('novo-titulo').value = ''; // Limpa o campo
        renderizarEstante();
    }

    function removerLivro(index) {
        livros.splice(index, 1);
        renderizarEstante();
    }

    // Iniciar a página
    renderizarEstante();
</script>

</body>
</html>
