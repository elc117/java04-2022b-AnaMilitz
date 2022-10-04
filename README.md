Você consegue identificar alguma redundância nos códigos (dentro de uma mesma classe ou em classes diferentes)?
Sim, ambas as classes "Professor" e "Student" possuem os atributos "name" e "userId".



O que aconteceria na classe Laboratory se tivéssemos outras categorias de membros além de estudantes e professores (técnicos, administradores, etc.)?
Precisariam ser criados novos private ArrayList<Tecnico> tecnicos, private ArrayList<Administrador> administradores e assim por diante. Além disso, também precisariam ser adicionados métodos addMember() específicos para estas categorias (ex: public void addMember(Administrador a)).
