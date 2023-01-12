# Projeto-Individual-Modulo-4

A proposta do projeto individual é criar um exemplo de banco de dados com tabelas relacionadas usando Foreing Key e responder algumas perguntas sobre o projeto proposto






As três perguntas são:




Existem outras entidades além dessas três?

R: Sim, existe, uma entidade na qual o registro dos professores se localiza, a entidade professores foi criada com o propósio de deixar a organição da modelagem do banco de dados melhor e mais coerente.




Quais são os principais campos e tipos?

R: Nesse projeto foram usados os tipos VARCHAR e INT.




Como essas entidades estão relacionadas?

R: A relação da entidade professores para a entidade cursos está Muitos x Muitos.
   A relação da entidade professores para a entidade Turmas está Muitos x Muitos.
   A relação da entidade Turmas para a entidade cursos está Muitos x 1(Um).
   A relação da entidade Alunos para a entidade Turmas está Muitos x 1(Um).




A entidade professores tem os seguintes registros:

professores_id INT
nome_professores VARCHAR(45)
materia VARCHAR(45)
turno VARCHAR(45)




A entidade cursos tem os seguintes registros:

cursos_id INT
programaçao VARCHAR(100)
administraçao VARCHAR(100)
marketing_digital VARCHAR(100)




A entidade Turmas tem os seguintes registros:

turma_id INT
turma 1 VARCHAR(45)
turma 2 VARCHAR(45)




A entidade Alunos tem os seguintes registros:

alunos_id INT
alunos_nome VARCHAR(45)
alunos_registro VARCHAR(45)
