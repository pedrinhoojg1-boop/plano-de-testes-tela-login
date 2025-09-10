# plano-de-testes-tela-login
Projeto para documentar casos de teste e um plano de testes para uma tela de login simples
# Plano de Testes: Tela de Login

Este repositório é um projeto de estudo para a disciplina de Design Profissional. O objetivo é aplicar conceitos fundamentais de Qualidade de Software (QA) na criação de um plano de testes e casos de teste para uma funcionalidade comum: a tela de login de um sistema.

---

## 🎯 Objetivo do Projeto

O foco deste projeto é documentar e estruturar um processo de teste para uma tela de login fictícia, contemplando:

- **Cenários de Teste:** Mapear as diferentes jornadas que um usuário pode seguir (login com sucesso, senha incorreta, e-mail inválido, etc.).
- **Casos de Teste:** Detalhar o passo a passo para cada teste, incluindo a ação esperada e o resultado esperado.
- **Relato de Bugs:** Simular como um bug seria reportado caso fosse encontrado durante os testes.

---

## 🛠️ Ferramentas e Conceitos Utilizados

Para a criação deste plano de testes, foram aplicados os seguintes conceitos e ferramentas de QA:

- **Técnicas de Teste Funcional:** Verificação dos requisitos da tela de login.
- **Design de Casos de Teste:** Escrita clara e objetiva dos passos para garantir a cobertura dos cenários.
- **Documentação em Markdown:** Utilização da linguagem Markdown para criar este documento de forma organizada.
- **Controle de Versão com Git/GitHub:** Uso da plataforma para armazenar e gerenciar a documentação do projeto.

---

## 🧪 Casos de Teste (Exemplos)

| ID   | Título do Teste                  | Passos                                                                                                | Resultado Esperado                                           |
| :--- | :------------------------------- | :---------------------------------------------------------------------------------------------------- | :----------------------------------------------------------- |
| CT01 | **Login com Credenciais Válidas** | 1. Acessar a página de login.<br>2. Inserir e-mail válido.<br>3. Inserir senha válida.<br>4. Clicar em "Entrar". | O usuário deve ser redirecionado para a página inicial (dashboard). |
| CT02 | **Login com Senha Inválida** | 1. Acessar a página de login.<br>2. Inserir e-mail válido.<br>3. Inserir senha **inválida**.<br>4. Clicar em "Entrar". | O sistema deve exibir a mensagem: "E-mail ou senha incorretos." |
| CT03 | **Login com E-mail em Branco** | 1. Acessar a página de login.<br>2. Deixar o campo de e-mail em branco.<br>3. Inserir senha válida.<br>4. Clicar em "Entrar". | O sistema deve exibir a mensagem: "O campo e-mail é obrigatório." |
