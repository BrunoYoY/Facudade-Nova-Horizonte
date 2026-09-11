# Requisitos de Segurança

## SR-001 — [Nome do requisito]
[As senha podem ser muito simples ]

**Requisito:**
[Criar um algoritmo que verifica a força da senha do usuario.] 
[Ou sempre que o login expirar é o usuario logar novamente mandar uma nova senha automatica no gmail do usuario.]

**Categoria:**
[autenticação, autorização, sessão.]

**Prioridade:**
[Crítica]
**Motivo:**
[priorizar as senhas do usuario ajudar muito na segurança é ja elimina varios problemas futuros.]

---

## SR-002 — [Nome do requisito]
[Alunos conseguem acessar documentos de outros alunos]

**Requisito:**
[O aluno tera seu proprio Gmail fornecido pela escola onde nesse gmail ele pode logar no site para consutar seu documento]

**Categoria:**
[autenticação,autorização,sessão.]

**Prioridade:**
[Critica]

**Motivo:**
[Pode ocorrer BO se arquivos de alunos vazar por alguem mal entencionado.]

---

## SR-003 — [Nome do requisito]
[Qualquer tipo de arquivo pode ser enviado]
**Requisito:**
[Fazer com que apenas arquivos (pdf e world) seja enviado é tambem apenas professores e admin.]

**Categoria:**
[Dados,Upload]

**Prioridade:**
[Critico]

**Motivo:**
[Risco de alteraçoes nos arquivos originais .]

---

## SR-004 — [Nome do requisito]
[Não existe autenticação em dois fatores]
**Requisito:**
[Manda uma confirmação por gmail para o usuario que estiver logando.]

**Categoria:**
[autenticação,autorização,sessão.]


**Prioridade:**
[Critica]

**Motivo:**
[So de saber a senha do usuario pode acessa o site.]

---

## SR-005 — [Nome do requisito]
[Não existe limite para arquivos enviados.]
**Requisito:**
[Os arquivos devem ter um limite por professor.]

**Categoria:**
[Autenticação,upload.]

**Prioridade:**
[Alta]

**Motivo:**
[Muitos arquivos podem sobrecarregar o site/sistema.]

---

## SR-006 — [Nome do requisito]
Não existe registros do logins dos usuarios
**Requisito:**
[Criar um especie de historico pro admin sobre todos que tiveram acesso nos ultimos dias e quais estao online.]

**Categoria:**
[logs,dados.]

**Prioridade:**
[Medio]

**Motivo:**
[saber quem esta online na hora de um possivel erro ou vazamentos de dados.]

---

## SR-007 — [Nome do requisito]
[As sessões dos usuários nunca expiram.]
**Requisito:**
[criar um algoritimo que faça resetar o login de todos os usuarios a cada saida do site ou 24h.]

**Categoria:**
[Dados,logs]

**Prioridade:**
[Critica]

**Motivo:**
[Pode ocorrer que usuario deixa seu celular logado e ter um vazamento de suas informaçoes pessoais.]

---

## SR-008 — [Nome do requisito]
Algumas mensagens de erro mostram informações técnicas do sistema
**Requisito:**
[Revisar o codigo e deixar o mesmo privado apenas para admin em caso de erro no sistema fazer o sistema ficar fora do ar ate corrigir o erro.]

**Categoria:**
[Dados.]

**Prioridade:**
[Critica]

**Motivo:**
[Pode vazar senhas é documentos.]
