<h2>:arrow_right: Perguntas a serem respondidas:</h2>

1º Existem outras entidades além dessas três?

R: Eu acredito que possuem mais relações em um curso além do aluno, turma e curso, neste diagrama eu também levei em consideração o instrutor, o responsavel pelo aprendizado da turma e as matriculas.

2º Quais são os principais campos e tipos?

ID - com o tipo INT (Um inteiro de tamanho normal)

Nome - com o tipo VARCHAR (Uma sequência de caracteres de texto de tamanho a ser definido)

Email - com o tipo VARCHAR (Uma sequência de caracteres de texto de tamanho a ser definido)

Valor_Hora - com o tipo INTEGER (Um grupo de tipos de dados)

Data - com o tipo DATE (Responsável por armazenar uma hora ou data)

Carga_Horária - com o timpo SMALLINT (Responsável por armazenar pequenos números inteiros)

cpf - com o tipo CHAR (Uma sequência de caracteres de texto de tamanho fixo)

preço = com o tipo DOUBLE (É um tipo númerico de base 2)

3º Como essas entidades estão relacionadas?

A- Comecei pelo objeto curso, a base para esse diagrama de relações. o mesmo possui Nome, Requisito, Carga Horaria e preço. O Requisito são os conhecimentos necessários que o aluno deve possuir, a carga horária é o tempo de curso e por fim o valor do mesmo.

B- A partir disto criei as outras tabelas interligadas ao curso, intrutores, matriculas, alunos e turmas. É importante citar que há uma relação direto entre turmas e matriculas, afinal só poderão haver vagar para novas matriculas se houverem turmas abertas, e também na matricula existe um campo que relaciona com o aluno, afinal para se ter uma matricula é necessário ter um aluno.

C- Na tabela turma e na tabela curso temos um campo em comum que é a carga_horaria, isso é feito por que a qualquer momento a carga horária de um curso pode ser alterada e isso poderia prejudicar as informações a fins de relatórios, afinal apesar da mudança de carga horária do curso a carga horária da turma se mantem.
