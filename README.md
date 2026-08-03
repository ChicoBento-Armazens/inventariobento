# Inventário Bento

Sistema web para gerenciamento e consulta de itens de inventário, desenvolvido com **React**, **Vite** e **React Router**. O projeto oferece uma interface simples para navegação entre páginas, visualização de produtos, consulta de detalhes e gerenciamento de perfil de usuário.

---

## Funcionalidades

- Página inicial com notícias e tutoriais
- Listagem de produtos
- Pesquisa e filtros de produtos
- Página individual para cada item do inventário
- Sistema de login
- Página de perfil do usuário
- Página de cadastro
- Header e Footer reutilizáveis
- Interface responsiva

---

## Tecnologias utilizadas

- React 19
- Vite
- React Router DOM
- HTML5
- CSS3
- JavaScript (ES6+)

---

## Estrutura do projeto

```
src/
│
├── images/
│
├── pages/
│   ├── cadastro/
│   ├── home/
│   ├── login/
│   ├── product/
│   ├── products/
│   ├── profile/
│   └── shared/
│
├── App.jsx
├── index.jsx
└── index.css
```

---

## Instalação

Clone o repositório:

```bash
git clone <url-do-repositorio>
```

Entre na pasta do projeto:

```bash
cd inventariobento
```

Instale as dependências:

```bash
npm install
```

---

## Executando o projeto

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

Depois abra o endereço informado pelo Vite no navegador (normalmente):

```
http://localhost:5173
```

---

## Build para produção

```bash
npm run build
```

Para visualizar a build:

```bash
npm run preview
```

---

## Rotas disponíveis

| Rota | Descrição |
|------|-----------|
| `/` | Página inicial |
| `/products` | Lista de produtos |
| `/product/:id` | Informações de um produto |
| `/login` | Login |
| `/profile` | Perfil do usuário |
| `/cadastro` | Cadastro |

---

## Organização

O projeto foi dividido em componentes reutilizáveis e páginas independentes, facilitando manutenção e futuras implementações.

Entre os componentes compartilhados estão:

- Header
- Footer
- Select personalizado
- Estilos compartilhados

---

## Próximas melhorias

- Integração com API
- Banco de dados
- Autenticação real
- Cadastro e edição de produtos
- Upload de imagens
- Pesquisa dinâmica
- Controle de estoque
- Histórico de alterações
- Sistema de permissões de usuários

---

## Desenvolvido por

Projeto desenvolvido para o sistema de inventário do **Colégio Técnico de Campinas "Bento Quirino" (COTUCA)**.
