# Project Management SaaS

**Project Management SaaS** é uma solução completa para gestão de projetos, oferecendo uma interface amigável, funcionalidades avançadas para controle de tarefas, equipes e prazos, e total acessibilidade.

## 📝 Índice
- [Sobre](#sobre)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Uso](#uso)
- [Acessibilidade](#acessibilidade)
- [Documentação da API](#documentação-da-api)
- [Contribuição](#contribuição)
- [Licença](#licença)

## 📖 Sobre

O **Project Management SaaS** foi desenvolvido para simplificar a organização e execução de projetos. Ele permite gerenciar equipes, acompanhar o progresso e garantir o cumprimento de prazos de maneira eficiente. Nosso objetivo é garantir acessibilidade, escalabilidade e fácil usabilidade para todos os usuários.

## ✨ Funcionalidades

- **Gerenciamento de Tarefas:** Criação, edição, e exclusão de tarefas com prazos e status de conclusão.
- **Gestão de Equipes:** Adição de membros, atribuição de tarefas e comunicação dentro do sistema.
- **Timeline e Calendário:** Visualize o andamento das tarefas em uma linha do tempo ou calendário interativo.
- **Relatórios e Insights:** Geração de relatórios de desempenho com insights automáticos sobre os projetos.
- **Acessibilidade:** Totalmente acessível para usuários com necessidades especiais, incluindo suporte a leitores de tela e navegação por teclado.

## 💻 Instalação

Siga os passos abaixo para rodar o projeto localmente:

### Pré-requisitos
- [Node.js](https://nodejs.org/) versão >= 14
- [Python](https://www.python.org/) versão >= 3.12
- [MySQL](https://www.mysql.com/) ou outro banco de dados compatível

### Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/JA-Solutions-Engine/project-management-saas.git
    ```

2. Instale as dependências:
    ```bash
    cd project-management-saas
    npm install
    ```

3. Configure o banco de dados em `config/database.php` e rode as migrações:
    ```bash
    npx sequelize db:migrate
    ```

4. Inicie o servidor:
    ```bash
    npm start
    ```

O projeto será executado em `http://localhost:3000`.

## 🚀 Uso

1. Faça login com sua conta.
2. Crie seu primeiro projeto e defina os membros da equipe.
3. Adicione e gerencie tarefas, visualizando-as na timeline ou no calendário.
4. Acompanhe o progresso por meio dos relatórios gerados automaticamente.

## 🦾 Acessibilidade

O **Project Management SaaS** foi projetado com a acessibilidade em mente, conforme as diretrizes da WCAG 2.1. Algumas das medidas adotadas:

- **Navegação por Teclado:** Todos os elementos interativos podem ser acessados através da navegação por teclado.
- **Leitor de Tela:** Textos alternativos são fornecidos para todos os elementos gráficos, e a estrutura de cabeçalhos é organizada logicamente.
- **Contraste de Cores:** Cores de alto contraste são usadas para garantir a legibilidade de textos e botões.
- **Ajuste de Texto:** Usuários podem aumentar ou diminuir o tamanho do texto sem perda de funcionalidade.

## 📚 Documentação da API

A API do **Project Management SaaS** segue o padrão REST. Aqui estão algumas das principais rotas:

### **Autenticação**
- `POST /api/login`: Faz o login de um usuário.
- `POST /api/register`: Registra um novo usuário.

### **Projetos**
- `GET /api/projects`: Lista todos os projetos do usuário.
- `POST /api/projects`: Cria um novo projeto.

### **Tarefas**
- `GET /api/tasks`: Lista todas as tarefas de um projeto.
- `POST /api/tasks`: Cria uma nova tarefa.
- `PUT /api/tasks/:id`: Atualiza uma tarefa existente.
- `DELETE /api/tasks/:id`: Exclui uma tarefa.

Mais detalhes estão disponíveis na [documentação completa](https://github.com/JA-Solutions-Engine/project-management-saas/wiki).

## 🤝 Contribuição

Sinta-se à vontade para contribuir com este projeto! Veja o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para mais informações.

1. Fork este repositório.
2. Crie sua branch (`git checkout -b minha-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
