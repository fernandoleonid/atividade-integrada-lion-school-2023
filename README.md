# Atividade integrada - SENAI 2023

![](https://repository-images.githubusercontent.com/618073290/a3f02c70-b7f2-4962-a5fa-ce29c81af351)

## Objetivo
A atividade tem como objetivo integrar as disciplinas de PWFE (Programação web Front-end) e PWBE (Programação web Back-end) do curso de desenvolvimento de sistemas do SENAI Jandira.

O projeto é o gerenciamento da escola Lion School, deverá ser realizado tanto o back-end como o front-end. 

---
## Projeto Front-end
Deverá consumir a API e criar as páginas conforme o designer feito no [figma](https://www.figma.com/file/KhTQbG1DY0MdAIGK73ZWp8/PWFE---Trabalho-Integrado?node-id=0%3A1).

### Critérios 
- [ ] Criou layout conforme designer feito no Figma?
- [ ] Os botões dos cursos são dinâmicos?
- [ ] Os cards são criados dinamicamente?
- [ ] A página com informações dos cursos foi criada dinamicamente?
- [ ] O filtro por status está funcional?
- [ ] Os nomes das variáveis, funções e arquivos tem valor semântico?
- [ ] A maioria das funções seguem as boas práticas como responsabilidade única?
- [ ] Foi criado o layout responsivo no Figma?
- [ ] Foi implementado a responsividade conforme planejado no Figma?
- [ ] Foi criado o filtro por ano?

Clique [aqui](https://reliable-yttrium-924.notion.site/7e8be653064c42eab044b543fa4391e1?v=2b3db2ab3f3048eea7b752613c817597) para acompanhar a correção

---
## Projeto Back-end
Deverá criar um servidor API implementando somente o método GET, contendo os seguintes end-points:

Método | End-point | Descrição 
---|---|---
**GET** | /v1/lion-school/cursos |  Recupera uma lista de todos os cursos oferecidos pela escola.
**GET** | /v1/lion-school/alunos |  Recupera uma lista de todos os alunos matriculados na escola.
**GET** | /v1/lion-school/alunos/{matricula} | Recupera informações de um aluno específico com base no número de matrícula.
**GET** | /v1/lion-school/alunos?curso={ds}: | Recupera uma lista de todos os alunos matriculados no curso especificado.
**GET** | /v1/lion-school/alunos?status={finalizado} | Recupera uma lista de todos os alunos com o status especificado.

> Obs.: A turma inteira deverá entrar em acordo para determinar o JSON de resposta de cada end-point


### Entregas
- [ ] Cronograma de atividades
- [ ] Documentação da API
- [ ] Postman 

---
### Desafio extra
- Publique o back-end na nuvem

### Professores
- [Fernando Leonid](https://github.com/fernandoleonid)
- [Marcel Teixeira](https://github.com/marcelnt)