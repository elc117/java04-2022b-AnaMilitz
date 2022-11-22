1. Você consegue identificar alguma redundância nos códigos (dentro de uma mesma classe ou em classes diferentes)?
Sim, ambas as classes "Professor" e "Student" possuem os atributos "name" e "userId".

2. O que aconteceria se fosse necessário armazenar outros atributos sobre estudantes e professores? (por exemplo, CPF, data de nascimento, telefone, etc?)
Seria necessário adicionar estes mesmos atributos para cada uma das classes Professor e Student, repentindo atributos que são comuns a ambos.

3. O que aconteceria na classe Laboratory se tivéssemos outras categorias de membros além de estudantes e professores (técnicos, administradores, etc.)?
Precisariam ser criados novos private ArrayList<Tecnico> tecnicos, private ArrayList<Administrador> administradores e assim por diante. Além disso, também precisariam ser adicionados métodos addMember() específicos para estas categorias (ex: public void addMember(Administrador a)). Ademais, seguindo a lógica utilizada para os membros de estudantes e professores, mais código seria repetido no armazenamento dos atributos destas novas categorias.
