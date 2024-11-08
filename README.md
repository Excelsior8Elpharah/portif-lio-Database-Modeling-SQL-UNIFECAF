# portifolio-Database-Modeling-SQL-UNIFECAF
Criando uma base de dados para que atenda um sistema de uma faculdade.

Título do Projeto:
Criando uma Base de Dados para que Atenda um Sistema de uma Faculdade
________________________________________
Projeto:
Os proprietários de uma faculdade precisam de um sistema que viabilize o armazenamento de informações sobre seus alunos, cursos, matérias e professores para que seja possível realizar controles básicos como montar turmas e armazenar notas dos alunos.
Com base no que foi apresentado, o objetivo é criar um banco de dados que ofereça suporte para que o sistema possa atender às necessidades do cliente. Abaixo estão as respostas detalhadas para cada questão proposta, além da modelagem sugerida.
________________________________________
3. Objetivos
3.1 Objetivos de Aprendizagem (Plano de Aprendizagem):
•	Análise de Requisitos: Identificar as necessidades do cliente e definir quais dados serão necessários.
•	Modelagem Conceitual: Estruturar as entidades e relacionamentos de forma clara, compreendendo como as informações se interconectam.
•	Modelagem Lógica: Definir as tabelas, atributos e relacionamentos que irão compor o banco de dados no sistema relacional.
________________________________________
1. Necessidades dos Clientes
a. Quais informações precisam ser armazenadas?
•	Dados dos alunos (nome, CPF, curso, contatos).
•	Informações dos professores (nome, formação, contatos).
•	Detalhes sobre cursos oferecidos e suas disciplinas.
•	Cadastro das turmas e seus respectivos professores e disciplinas.
•	Matrículas de alunos em turmas específicas.
•	Notas obtidas pelos alunos ao longo das disciplinas.


b. Quais os dados precisam ser guardados?
•	Alunos: Nome, data de nascimento, CPF, e-mail, telefone e curso vinculado.
•	Professores: Nome, formação, e-mail e telefone.
•	Cursos: Nome e duração.
•	Disciplinas: Nome, carga horária e curso ao qual pertence.
•	Turmas: Disciplina, professor, semestre/ano.
•	Matrículas: Aluno, turma e data de matrícula.
•	Notas: Avaliações e notas obtidas pelos alunos.
c. O que será feito com os dados posteriormente?
•	Controle acadêmico: Armazenar notas e aprovações.
•	Gestão de professores: Acompanhar a alocação de professores em turmas.
•	Relatórios: Gerar históricos escolares e calcular médias.
•	Planejamento: Auxiliar na alocação de alunos e professores nas turmas futuras.
