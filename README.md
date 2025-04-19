# **SerieNow** 📺🎬

**Projeto de Gerenciamento de Séries Assistidas**

> O **SerieNow** é uma aplicação para gerenciar suas séries favoritas, acompanhar o progresso dos episódios assistidos e armazenar dados de forma eficiente e organizada. A aplicação possui autenticação de usuários, uma interface intuitiva e um back-end robusto, garantindo a melhor experiência para o usuário.

---

## **🔧 Tecnologias Utilizadas**

### **Front-End:**
- **HTML** 🖥️ e **CSS** 🎨: Responsáveis pela estrutura e design da aplicação, com foco em **responsividade** para dispositivos móveis e desktop.
- **JavaScript** ⚡: Tornando a aplicação interativa, permitindo que o usuário adicione, remova e interaja com as séries de sua lista.
- **Vue.js** (opcional) 🔄: Framework JavaScript que poderá ser integrado futuramente para aumentar a reatividade e modularidade da aplicação, oferecendo uma interface mais dinâmica.

### **Back-End:**
- **Node.js** 🚀: Plataforma para o desenvolvimento do back-end, escolhida pela sua performance e escalabilidade. A arquitetura será **serverless**, usando funções no Vercel.
- **Express.js** 🌐: Framework para criar rotas e APIs para manipular dados de usuários e séries de maneira simples e eficiente.
- **MongoDB Atlas** 📊: Banco de dados **NoSQL** na nuvem, ideal para armazenar dados das séries e dos usuários.

### **Deploy:**
- **Vercel** 🌍: Plataforma de deploy contínuo que facilita a hospedagem tanto do front-end quanto do back-end, usando funções serverless para o back-end.

### **Autenticação:**
- **JWT (JSON Web Token)** 🔒: Para garantir a segurança nas sessões de usuários, permitindo o registro, login e autenticação contínua na plataforma.

---

## **✨ Funcionalidades**

- **Cadastro de Usuário** 📝: Permite ao usuário criar uma conta para salvar suas séries favoritas e acompanhar o progresso.
- **Login e Autenticação** 🔑: Login seguro com email e senha, usando JWT para uma autenticação eficiente.
- **Gerenciamento de Séries** 📚: O usuário pode adicionar novas séries à sua lista, marcar episódios como assistidos e adicionar notas.
- **Visualização de Progresso** 📊: Acompanhamento do progresso das séries, mostrando episódios assistidos e restantes.
- **Interface Responsiva** 📱💻: A aplicação se adapta bem tanto a dispositivos móveis quanto a desktops, garantindo boa experiência em qualquer formato de tela.

---

## **📂 Estrutura do Projeto**


/public
    index.html         # Página inicial
    style.css          # Estilo global da aplicação

/src
    /assets             # Imagens e arquivos estáticos
    /components         # Componentes Vue.js (se utilizado)
    /services           # Funções de comunicação com o back-end
    /views              # Páginas principais da aplicação

/backend
    /controllers        # Lógica de controle para autenticação e manipulação de séries
    /models             # Definições dos modelos de dados (Usuário, Série)
    /routes             # Definição das rotas da API
    /services           # Funções para interação com o banco de dados
    /functions          # Funções serverless para o back-end
    /config             # Configurações do banco de dados e autenticação
---

## **🚀 Passos para Rodar o Projeto Localmente**

1. Clone o repositório
bash
Copiar
Editar
git clone https://github.com/usuario/projeto-series.git
cd projeto-series
2. Instale as dependências do front-end
bash
Copiar
Editar
cd frontend
npm install
3. Instale as dependências do back-end
bash
Copiar
Editar
cd backend
npm install
4. Inicie o servidor localmente
Para o front-end:

bash
Copiar
Editar
cd frontend
npm run dev
Para o back-end:

bash
Copiar
Editar
cd backend
npm run dev
Isso iniciará o servidor localmente na porta 3000 (ou outra que você configurar).

🌐 Deploy no Vercel
1. Crie uma conta na Vercel
Acesse Vercel e crie uma conta se ainda não tiver.

2. Conecte o repositório ao Vercel
No dashboard da Vercel, clique em "New Project".

Selecione o repositório do projeto no GitHub ou faça o upload manualmente.

Configure as variáveis de ambiente, se necessário (como JWT Secret, MongoDB URI).

3. Deploy do front-end e back-end
O Vercel cuidará do deploy automaticamente.

Para o back-end, configure as funções serverless no Vercel Functions.

Para o front-end, o Vercel cuidará da construção e hospedagem de arquivos estáticos (HTML, CSS, JS).

## **🚀 Tecnologias Futuras e Melhorias**

Vue.js (ou React) poderá ser integrado para uma experiência de usuário mais dinâmica.

Comentários e avaliações para as séries.

Integração com API de informações sobre séries (exemplo: TMDb API).

Implementação de notificações por e-mail para avisar sobre novos episódios das séries favoritas.

## **🔚 Conclusão**

Este projeto foi desenhado para ser simples e funcional, mas também flexível para crescer. Usando tecnologias modernas como Node.js, MongoDB, e Vercel, conseguimos criar uma aplicação escalável e de excelente performance.

A escolha da arquitetura serverless e a utilização de JWT garantem que o projeto seja de baixo custo, seguro e fácil de escalar, tornando-o ideal para desenvolvimento e integração com outras plataformas.
