# Sistema de Login e Registro

Projeto desenvolvido com foco na simulação de um fluxo real de autenticação de usuários, com ênfase em *validação de formulários*, *controle de estado* e *experiência do usuário*.

---

## Objetivo do Projeto

Demonstrar capacidade de:

* Implementar regras de validação no front-end
* Organizar código de forma clara e escalável
* Trabalhar com estados e feedback visual
* Simular regras de negócio comuns em aplicações reais

---

## Funcionalidades

### Login

Campos:

* Email
* Senha

Validações:

* Email obrigatório e em formato válido
* Senha obrigatória com no mínimo 6 caracteres

Regras:

* Verificação de existência do email
* Verificação de correspondência da senha
* Utilização de lista mockada de usuários em memória

Comportamento:

* Sucesso ao autenticar com credenciais válidas
* Erro para email inexistente ou senha incorreta

Feedback ao usuário:

* Mensagens de erro abaixo dos campos
* Botão desabilitado enquanto o formulário for inválido
* Indicador simples de carregamento 

---

### Registro

Campos:

* Nome
* Email
* Senha
* Confirmação de senha

Validações:

* Nome obrigatório com mínimo de 3 caracteres
* Email válido e não duplicado
* Senha com mínimo de 6 caracteres
* Confirmação de senha igual à senha informada

Regras:

* Validação completa antes do envio
* Bloqueio de cadastro com email já existente
* Inserção do novo usuário na lista mockada

Comportamento:

* Cadastro realizado com sucesso
* Redirecionamento para login

---

## Estrutura Técnica

* Componentização:

  * Input
  * Button
  * Form
* Gerenciamento de estado 
* Separação entre:

  * Lógica de validação
  * Lógica de submissão

---

## Critérios de Qualidade

* Formulários não permitem envio inválido
* Mensagens de erro claras e objetivas
* Login funciona apenas com credenciais válidas
* Registro impede emails duplicados
* Código organizado, legível e reutilizável
* Fluxo intuitivo para o usuário final

---

## Tecnologias Utilizadas

* HTML
* CSS
* JavaScript

---

## Próximos Passos

* Integração com backend real
* Persistência de dados
* Testes unitários
