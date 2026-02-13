# Marcos Martin - Vitrine Autoral

Este é um projeto de portfólio web single-page (SPA) desenvolvido para o autor **Marcos Martin**. O objetivo é apresentar suas obras literárias de forma elegante, moderna e interativa, permitindo também o gerenciamento de conteúdo através de um painel administrativo.

## 🚀 Funcionalidades

### Área Pública (Vitrine)
*   **Hero Section Imersiva**: Apresentação visual impactante do autor com animações e links rápidos.
*   **Catálogo de Livros**: Exibição das obras em cards com efeito de vidro (glassmorphism).
*   **Busca e Filtros**:
    *   Barra de pesquisa em tempo real (busca por título ou descrição).
    *   Filtros por categoria/gênero (chips interativos).
*   **Detalhes da Obra**: Modal rico com sinopse completa e botão para solicitar exemplar via WhatsApp.
*   **Design Responsivo**: Layout otimizado para celulares, tablets e desktops.
*   **Tela Cheia**: Botão de alternância fullscreen com ícones dinâmicos.
*   **Scroll Automático**: A página sempre inicia no topo ao recarregar.

### Painel Administrativo
*   **Gestão de Livros (CRUD)**: Adicionar, editar, excluir e reordenar livros.
*   **Perfil do Autor**: Atualizar biografia e foto do autor.
*   **Upload de Imagens**: Integração com Firebase Storage para capas de livros e foto de perfil.
*   **Alteração de Senha**: Possibilidade de alterar a senha de administrador (simulação local).

## 🛠 Tecnologias Utilizadas

*   **Frontend**: HTML5 Semântico, JavaScript (ES6+ Modules).
*   **Estilização**: Tailwind CSS (via CDN) com customizações de tema (Dark Mode, Glassmorphism, Cores Slate & Amber).
*   **Backend & Banco de Dados**: Firebase (Firestore, Authentication, Storage).
*   **Fontes**: Inter e Playfair Display (Google Fonts).
*   **Tema**: `color-scheme: dark` para garantir consistência visual em todos os elementos nativos do navegador.

## 🔑 Acesso Administrativo

Para acessar o painel de gerenciamento, clique no botão "Admin" (ou ícone de cadeado no mobile) e utilize as credenciais abaixo:

*   **Usuário**: `marcosmartin`
*   **Senha**: `thiagocucabeludo`

> **Nota**: O sistema utiliza autenticação anônima do Firebase para visitantes e autenticação simulada no cliente para o admin, visando simplicidade neste protótipo.

## 📦 Como Rodar o Projeto

1.  Clone este repositório ou baixe os arquivos.
2.  Abra o arquivo `index.html` em seu navegador favorito.
3.  Para uma melhor experiência (evitar bloqueios de CORS em alguns navegadores), recomenda-se usar um servidor local simples, como o "Live Server" do VS Code ou:

```bash
# Com Python
python3 -m http.server
# Com Node.js (http-server)
npx http-server .
```

## 👨‍💻 Desenvolvido por

**Renato Chagas** — [kenicode](https://github.com/kenicode)
