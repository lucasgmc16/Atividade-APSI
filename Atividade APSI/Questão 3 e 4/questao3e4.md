### 3- Documente os requisitos usando histórias de usuários.

História 1:
    -> Como cliente da Petclinic, gostaria de acessar facilmente as receitas e exames médicos do meu pet, assim não dependerei de atendimento.

História 2:
    -> Como veterinário, gostaria de acessar todas as consultas da agenda, assim podendo marcar novas consultas em dias disponíveis.
    
História 3:
    -> Como dono da clínica, gostaria de possuir uma maneira de gerênciar meus funcionários e suas atividades, assim podendo ajustar salários e ofertar promoções.
    
História 4:
    -> Como funcionário, gostaria de poder modificar cadastros clínicos anteriores, assim podendo corrigir qualquer tipo de erro cadastrado anteriores.
    
História 5:
    -> Como dono da clínica, gostaria de possuir uma maneira de gerênciar meus clientes e suas atividades, assim podendo ter controle do fluxo de clientes durante o mês.
    
História 6:
    -> Como sistema, gostaria de exigir o login na tela inicial, assim tendo o total controle dos acessos e seus tipos.

História 7:
    -> Como veterinário, gostaria de atribuir um código para cada pet, assim tendo controle total sobre a situação do pet.

### 4- Para cada história de usuário, descreva o mínimos de 3 critérios de aceitação usando BDD. 

Critérios de aceitação:

    História 1:
        - Na página inicial, eu gostaria que houvesse uma área que filtrasse por data de consulta as receitas e exames médicos que foram lançadas pelo veterinário, retornando a data, o nome do veterinário, o nome do meu pet, o nome do medicamento e nome do exame.

        - Após acessar a área citada anteriormente, quero poder escolher o exame de qualquer pet que já cadastrei, assim podendo especificar qual dos meus pets eu quero consultar.

        - Após acessar a área e informas presentes, quero poder deletar as consultar mais antigas.

    História 2:
        - Na página inicial, eu gostaria que houvesse uma área com a agenda das consultas para os funcionários, assim podendo marcar consultas em dias livres e desmarcar as consultas marcadas caso apareça um imprevisto.

        -Na área com a agenda das consultas para os funcionários, eu gostaria de poder editar as informações e datas de consultas, assim podendo reagender as consultas caso seja necessário.

        -Na área com a agenda das consutlas para os funcionários, eu gostaria de poder acessar os dados das consultas já cadastradas, para poder ter um melhor acompanhamento da situação do pet.

    História 3:
        - Na página inicial, eu gostaria de poder me cadastrar como dono para poder ter acesso a uma área de gerenciamento dos meus funcionários, assim podendo acessar informações como o nome, cargo, carga hóraria, serviços e salários.

        - Na área de gerenciamento de funcionários, eu gostaria de poder inserir e deletar os dados dos funcionários no sistema, assim podendo controlar a contratação de novos funcionários e demissão dos antigos.

        - Na área de gerenciamento de funcionários, eu gostaria de ser aletardo caso eu tente inserir funcionários que já estão no sistema ou tente deletar funcionários que não estão no sistema.
        
    História 4:
        - Na área de históricos, eu gostaria de ter a opção de editar as informações que já foram inseridas, assim eu poderei corrigir erros e adicionar informações.
        
        -Quando eu estiver editando um histórico, eu gostaria de receber um aviso caso eu tente editar uma informação imporante que não deve ser editada, assim evitando futuros problemas no sistema.
        
        -Quando eu estiver editando um histórico, eu gostaria de receber um aviso caso eu deixe algum campo em branco, assim evitando a falta de informações no histórico. 
        
    História 5:
        -Quando eu estiver na área de gerenciamento de cliente, eu gostaria de saber quantas vezes o cliente visitou a clínica e qual pet foi o paciênte, assim eu terei mais controle do fluxo de clientes.
        
        -Quando eu estiver na área de gerenciamento de cliente, eu gostaria de ter um campo para buscar o cliente de acordo com seu histórico de cadastro, assim eu consigo encontrar um cliente específico de maneira mais rápida.
        
        -Quando eu estiver na área de gerenciamento de cliente, eu gostaria poder editar o cadastro do cliente, assim podendo adicionar e corrigir informações sobre os clientes. 
        
    História 6:
        -Quando estiverem na tela inicial do sistema, o sistema pedirá exibirá uma tela de login e a opção de criar conta, assim será sempre necessário logar em uma conta para utilizar o sistema.
        
        -Quando o usuário for fazer login, o sistema pedirá para ele especifiar o tipo de usuário que ele é, assim tendo um maior controle de contas e cargos.
        
        -Quando o usuário usar o sistema por 3 dias, o sistema deverá pedir para o usuário utilizar um autenticador, assim garantindo a segurança da conta. 
        
    História 7:
        -Quando eu conferir a consulta de um pet, quero clicar em um campo para digitar o código de um determinado animal, assim expondo o histórico de consultas.
        
        -Quando eu pesquisar sobre um pet, quero ter acesso a todo o histórico do pet, assim vou saber quais exames, consultas e remédios foram passados.
                
        -Quando eu conferir o perfil de um pet, quero ter acesso a todas informações cadastradas do animal, assim podendo estudar mais sobre o caso.
