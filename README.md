# Back-end-Listagem-e-cadastros-de-usuarios-

Essa semana foi muito produtiva construí um Back-end de cadastro de agendamento,listagem de agendamento com NodeJS e Typescript,aplicando alguns conceitos muito importantes; 
# SRP (Single Responsability Principle)
Esse princípio zela que uma classe deve possuir apenas uma responsabilidade. Exemplo: Ao criar um service chamado  
# SoC (Separation of Concerns):
Esse princípio zela pela separação de responsabilidades de cada arquivo. Exemplo: as rotas não devem ser responsáveis por lidar com a persistência dos dados, isso fica por conta do repositório. Já o repositório não é responsável pela tratativa das regras de negócio, isso é responsabilidade dos Services;  
# DIP (Dependency Inversion Principle): 
Esse princípio zela que uma entidade dependa apenas de abstrações, não de implementações. Exemplo: Ao atribuir ao repositório a comunicação com o Banco de dados, o Service precisa interagir apenas com essa abstração, sem precisar criar uma nova instância e realizar as ações diretamente;
