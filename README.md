# Projeto-Individual-4
Criação de um diagrama em SQL.

Existem outras entidades além dessas três?   
Sim, mais 2. Matrículas e Professores

Quais são os principais campos e tipos?   
Nome   ⇨   VARCHAR
Sobrenome   ⇨   VARCHAR
Data nascimento   ⇨   DATE
Cpf  ⇨   INT
Telefone   ⇨   INT

Como essas entidades estão relacionadas?  
Alunos 1:N Turma;
Alunos 1:N Curso;
Aluno 1:1 Matrícula;
Matrícula 1:1 Turmas; 
Professores N:N Cursos;
Professores N:N Turmas 
