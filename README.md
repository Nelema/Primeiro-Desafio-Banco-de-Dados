## Primeiro-Desafio-Banco-de-Dados

**Desafio Banco de Dados Ecommerce Potência Tech

##Descrição do Desafio E-commerce(EMPRESA)
	
 ***Replique a modelagem do projeto lógico de banco de dados para o cenário de e-commerce. Fique atento as definições de chave primária e estrangeira, assim como as constraints presentes no cenário modelado. Perceba que dentro desta modelagem haverá relacionamentos presentes no modelo EER. Sendo assim, consulte como proceder para estes casos. Além disso, aplique o mapeamento de modelos aos refinamentos propostos no módulo de modelagem conceitual.
	
 ***Assim como demonstrado durante o desafio, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas dos que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:

***Modelagem Conceitual

##Nessa etapa, pode-se representar textualmente a modelagem ou ainda, usando um diagrama entidade relacionamento simplificado, assim como:

## Este projeto foi organizado textualmente para facilitar a compreensão do Cliente:
## A “Empresa” está sendo organizada em DEPARTAMENTO  e cada Depto tem um nome, um número,  um empregado que o gerencia e a data do início da gerência.
## Deseja-se guardar a data na qual o EMPREGADO começa a gerenciar o departamento.
##Um Departamento pode estar em vários locais.
## Um Departamento controla um número de PROJETOS, os quais possuem número, nome, localização e o número do departamento.
##Um EMPREGADO é caracterizado por nome, minicial, unome, ssn, data de nascimento, endereço, sexo, salário, superssn, dno.
##Os EMPREGADOS podem  estar vinculados a mais de um projeto, e um projeto tem mais de um empregado. 
##  O  empregado pode possuir DEPENDENTE com as seguintes atributos; nome, sexo, data nascimento, parentesco, essn.

