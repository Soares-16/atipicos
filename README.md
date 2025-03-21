-- Blog Coletivo com Flask e SQLite --

Este é um blog coletivo onde os considerados Atipicos pela sociedade, podem trocar experiencia entre si, podem postar conteudos para o bem comum, desenvolvido com Flask e SQLite, permitindo a criação, edição e exclusão de posts.

--Tecnologias Utilizadas--

- Python
- Flask
- SQLite
- HTML/CSS (para templates)

-- Como Executar o Projeto--

-- 1. Clonar o Repositório--

```sh
git clone https://github.com/Soares-16/atipicos.git
cd atipicos
```
-- 2. Criar e Ativar um Ambiente Virtual--

```sh
python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
```

-- 3. Instalar Dependências --

```sh
pip install flask
```

-- 4. Criar o Banco de Dados--

```sh
python -c "from app import init_db; init_db()"
```

-- 5. Rodar o Servidor Flask --

```sh
python app.py
```

Acesse o blog no navegador: [http://127.0.0.1:5000](http://127.0.0.1:5000)

-- Estrutura do Projeto--

```
/Atipicos
│── app.py            # Código principal da aplicação
│── schema.sql        # Script de criação do banco de dados
│── templates/        # Arquivos HTML
│   │── index.html    # Página inicial
│   │── create.html   # cria posts
│   │── edit.html     # edita posts
│── static/           # Arquivos CSS e JS (se necessário)
│── README.md         # Documentação do projeto
```

--Funcionalidades --

✅ Criar novos posts 
✅ Listar posts existentes 
✅ Editar posts
✅ Excluir posts

-- Melhorias Futuras --

- Autenticação de usuários
- Melhor design com CSS
- Filtros e categorias de posts

-- Licença--

Este projeto é de código aberto e pode ser modificado conforme necessário. 

