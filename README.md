# Trabalho-indivudal-modulo-4---banco-de-dados

Tabela Cursos: ID(INT) / Nome_do_curso (VARCHAR) / Professores (VARCHAR)
Tabela Alunos: ID(INT) / nome (VARCHAR) / Foto (VARCHAR) Ativo (BOOLAN)
Tabela Turmas: ID(INT) / Quantidade_de_alunos (INT) / Turno (VARCHAR) / Curso (VARCHAR)

Relações:

Cursos está relacionado a Alunos:
  Professores(VARCHAR) <--> Nome_aluno
  
Turmas está relacionado a Alunos:
  Nome_aluno <--> Quantidade_de_alunos
  
Cursos está relacionados a Turmas:
  Professores <--> Curso
  
