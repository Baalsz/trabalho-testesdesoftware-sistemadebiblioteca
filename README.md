# trabalho-testesdesoftware-sistemadebiblioteca
Inclui sistema Python, testes pytest, documentação e interface React

Instalar:

# Instalação Rápida (Nova Máquina)

Guia breve para executar o projeto em outro computador.

## 1) Pré-requisitos

- **Git** instalado
- **Python 3.10+**
- **Node.js 18+** e **npm**

## 2) Abrir a pasta do projeto

Copie o projeto para a nova máquina e abra a pasta `trabalhomalerba` no terminal/IDE.

## 3) Back-end / testes (Python)

Instale dependências e execute os testes:

```bash
pip install -r requirements.txt
pytest -v
```

### Credenciais de admin (sistema Python)

- E-mail: `admin@biblioteca.com`
- Senha: `admin123`

## 4) Front-end (React)

Entre na pasta `web/` e rode:

```bash
cd web
npm install
npm run dev
```

Abra o endereço mostrado no terminal (geralmente `http://localhost:5173`).

## 5) Build de produção (opcional)

```bash
cd web
npm run build
```

## 6) Problemas comuns

- **"Credenciais inválidas"**: confira e-mail/senha e se o usuário existe.
- **Erro de dependência Python**: confirme versão do Python e rode `pip install -r requirements.txt`.
- **Erro no React**: apague `web/node_modules`, rode `npm install` novamente.

---

Arquivo recomendado para incluir no GitHub junto com `README.md`.


Admin padrão criado automaticamente ao iniciar Biblioteca:
e-mail: admin@gmail.com
senha: admin1234

---

User Comum:
e-mail: maria@email.com
senha: senha123
