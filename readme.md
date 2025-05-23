# Atividade: Modelagem de Banco de Dados - Sistema de Gestão Escolar

📚 Contexto: <br>

Você foi contratado para desenvolver o modelo de dados de um sistema de gestão escolar que permitirá o gerenciamento de alunos, professores, disciplinas, notas e infraestrutura da escola.

O sistema deve armazenar informações sobre pessoas, turmas, disciplinas, matrículas, notas, salas, horários, entre outros.

⸻

✅ Requisitos: <br>
	1.	Cada aluno pode estar matriculado em várias turmas. <br>
	2.	Cada turma pode ter vários alunos e é associada a um professor. <br>
	3.	Cada professor pode lecionar várias disciplinas. <br>
	4.	Cada disciplina pode ser ofertada em várias turmas. <br>
	5.	Cada turma ocorre em uma sala específica. <br>
	6.	A nota de cada aluno é registrada por disciplina e turma. <br>
	7.	A escola possui várias salas, com capacidade e tipo de infraestrutura. <br>
	8.	Deve ser possível controlar os horários de cada turma. <br>
	9.	Existem funcionários que não são professores, como secretários e diretores. <br>
	10.	O endereço de cada pessoa (aluno, professor ou funcionário) deve ser armazenado. <br>
	11.	A escola possui vários cursos, compostos por várias disciplinas. <br>
	12.	A matrícula do aluno está associada a um curso. <br>

⸻

✅ Tabelas que devem ser criadas: <br>
	1.	Aluno <br>
	2.	Professor <br>
	3.	Funcionario <br>
	4.	Endereco <br>
	5.	Curso <br>
	6.	Disciplina <br>
	7.	Turma <br>
	8.	Sala <br>
	9.	Matricula <br>
	10.	Nota <br>
	11.	Horario <br>
	12.	Turma_Disciplina (para representar a associação N:N entre Turma e Disciplina) <br>

⸻

✅ O que entregar: <br>
	•	O diagrama entidade-relacionamento (ER) com todas as 12 tabelas. <br>
	•	Indicação de: <br>
	•	Chaves primárias <br>
	•	Chaves estrangeiras <br>
	•	Relacionamentos e cardinalidades. <br>
	•	Nome claro para cada atributo. <br>
	•	Tipos básicos de dados para cada coluna (ex.: INT, VARCHAR, DATE). <br>

⸻

✅ Dicas: <br>
	•	Use notação padrão de ER (Crow’s Foot, por exemplo). <br>
	•	Pense bem nas entidades que compartilham características (por exemplo, Aluno, Professor e Funcionario podem herdar atributos de uma entidade Pessoa — opcional). <br>
	•	Considere o uso de tabelas de junção para relacionamentos muitos-para-muitos. <br>
	•	Pode usar ferramentas como: Lucidchart, Draw.io, MySQL Workbench, ou qualquer outra de sua preferência. <br>

⸻

✅ Exemplo de relacionamentos importantes: <br>
	•	Um aluno tem um endereço. <br>
	•	Um professor tem um endereço. <br>
	•	Uma matrícula pertence a um aluno e a um curso. <br>
	•	Uma turma acontece em uma sala e possui horários. <br>
	•	Um professor leciona várias disciplinas. <br>
	•	Um aluno recebe notas em cada disciplina que cursa. <br>
