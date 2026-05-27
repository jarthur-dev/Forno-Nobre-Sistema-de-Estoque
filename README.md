# Forno-Nobre-Sistema-de-Estoque
Um sistema de estoque básico para uma padaria com controles de nível de acesso "Administrador/Funcionário".

# 🥖 Forno Nobre - Sistema de Gestão de Estoque

O **Forno Nobre** é uma aplicação web desenvolvida para facilitar o controle de insumos em padarias artesanais. O sistema permite o monitoramento de estoque em tempo real, auditoria de movimentações e gestão de acessos.

## 🚀 Funcionalidades

- **Gestão de Estoque:** Cadastro de insumos com alertas automáticos de quantidade mínima.
- **Níveis de Acesso:** Diferenciação funcional entre Administradores e Funcionários.
- **Histórico Completo:** Registro detalhado de todas as entradas e saídas (quem, quando e quanto).
- **Sistema de Solicitações:** Alterações de perfil de usuários passam por aprovação prévia do administrador.
- **Interface Responsiva:** Notificações visuais (badges) para pendências administrativas.

## 🛠️ Tecnologias Utilizadas

- **Backend:** Python com Flask
- **Banco de Dados:** SQLite com SQLAlchemy (ORM)
- **Frontend:** HTML5, CSS3, Bootstrap 5 e FontAwesome
- **Controle de Versão:** Git/GitHub

## 📦 Como rodar o projeto

1. Clone o repositório:
git clone https://github.com/jadevbuilds/Forno-Nobre-Sistema-de-Estoque.git

## 📸 Visual da Aplicação

### 🔐 Tela de Acesso (Login)
*Interface limpa e segura para autenticação de usuários, diferenciando acessos entre Administradores e Funcionários.*
![Login](static/img/readme/login_page.jpeg)

*Interface limpa e segura para a criação de um novo usuário no sistema.*
![Cadastro](static/img/readme/cadastro_page.jpeg)

### 📦 Controle de Estoque
*Visualização completa com gráficos volumétricos integrados, listagem de insumos, fluxo rápido de movimentação (entrada/saída) e botões de ação dinâmica.*
![Estoque Atual](static/img/readme/estoque_atual.jpeg)

### ✏️ Cadastro de Insumos
*Modal moderno integrado para cadastrar um novo insumo ao sistema Forno Nobre.*
![Editar Insumo](static/img/readme/cadastro_insumo.jpeg)

### 👤 Perfil e Notificações Administrativas
*Área personalizada onde o Administrador visualiza notificações de solicitações pendentes e gerencia seus dados.*
![Perfil](static/img/readme/perfil_page.jpeg)

### 📝 Histórico de Movimentações
*Registro detalhado de todas as operações realizadas, garantindo a auditoria completa do estoque.*
![Histórico](static/img/readme/historico_page.jpeg)