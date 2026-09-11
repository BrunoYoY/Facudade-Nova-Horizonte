# Atividade — Requisitos de Segurança de Aplicações

## Objetivo

Criar uma pequena análise de segurança de uma aplicação fictícia e identificar quais requisitos de segurança ela deveria possuir.

O trabalho será desenvolvido em um repositório no **GitHub**.

---

## Cenário

A Faculdade **Horizonte** possui um sistema web utilizado por alunos, professores e funcionários.

O sistema permite:

* Fazer login;
* Consultar informações acadêmicas;
* Consultar notas e faltas;
* Enviar documentos;
* Consultar documentos;
* Gerenciar usuários.

Existem três tipos de usuários:

* **Administrador:** possui acesso completo ao sistema.
* **Professor:** pode consultar informações das suas turmas e lançar notas e faltas.
* **Aluno:** pode consultar suas notas, faltas e documentos.

Atualmente, o sistema possui alguns problemas:

1. As senhas podem ser muito simples.
2. Não existe autenticação em dois fatores.
3. Alunos conseguem acessar documentos de outros alunos.
4. Qualquer tipo de arquivo pode ser enviado.
5. Não existe limite para arquivos enviados.
6. Não existem registros dos logins dos usuários.
7. As sessões dos usuários nunca expiram.
8. Algumas mensagens de erro mostram informações técnicas do sistema.

## Tarefa

Crie um repositório no GitHub chamado:

`security-requirements`

No repositório, crie os seguintes arquivos:

```text
README.md
requirements.md
```