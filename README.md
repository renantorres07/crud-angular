# Projeto CRUD em Angular 9

Este projeto é um exemplo de aplicação CRUD (Create, Read, Update, Delete) desenvolvida utilizando Angular 9. Ele demonstra a implementação básica de operações CRUD em uma aplicação web.

## 📋 Sumário

1. [Visão Geral](#visão-geral)
2. [Pré-requisitos](#pré-requisitos)
3. [Instalação](#instalação)
4. [Configuração do Ambiente](#configuração-do-ambiente)
5. [Como Executar](#como-executar)
6. [Como Usar](#como-usar)
7. [Tecnologias Utilizadas](#tecnologias-utilizadas)
8. [Contribuição](#contribuição)
9. [Licença](#licença)

## 📝 Visão Geral

Este projeto ilustra como criar uma aplicação CRUD básica usando Angular 9. Ele inclui componentes para listar, adicionar, editar e deletar itens.

## ✅ Pré-requisitos

Antes de começar, você precisa ter o Node.js e o Angular CLI instalados em sua máquina:

```bash
node -v
ng version
```

Se você não tiver o Angular CLI instalado, pode instalá-lo com o comando:

```bash
npm install -g @angular/cli
```

## ⚙️ Instalação

1. Clone este repositório para sua máquina local:

```bash
git clone https://github.com/renantorres07/crud-angular.git
cd crud-angular
```

2. Instale as dependências do projeto:

```bash
npm install
```

## 🛠️ Configuração do Ambiente

1. Crie um arquivo `.env` na raiz do projeto e defina as variáveis de ambiente necessárias, como a URL da API.

Exemplo:

```
API_URL=http://localhost:3000/api
```

2. Atualize os serviços para usar essas variáveis de ambiente.

## 🚀 Como Executar

Para executar a aplicação, use o comando:

```bash
ng serve
```

A aplicação estará disponível em `http://localhost:4200`.

## 📚 Como Usar

1. **Adicionar Item**: Clique no botão "Adicionar" e preencha o formulário.
2. **Listar Itens**: Acesse a página principal para ver a lista de itens.
3. **Editar Item**: Clique no botão "Editar" ao lado do item que deseja modificar.
4. **Deletar Item**: Clique no botão "Deletar" ao lado do item que deseja remover.

## 🛠️ Tecnologias Utilizadas

- Angular 9
- Angular CLI
- TypeScript
- HTML
- CSS

## 🤝 Contribuição

Se você deseja contribuir para este projeto, siga estas etapas:

1. Faça um fork do repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adicionei uma nova feature'`).
4. Faça um push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.

---

Obrigado por usar este projeto como exemplo! Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue no GitHub.
