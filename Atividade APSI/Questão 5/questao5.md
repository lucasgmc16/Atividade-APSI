### 5- Documente os seguintes Casos de Uso: A)Cadastrar Medicamentos, B)Realizar cadastro de Funcionários, C)Gerenciar folha de pagamento.

Caso de uso "A":

    Ator: Funcionário

    Fluxo normal:
    1- Recebe os medicamentos.
    2- Desembala os pacotes com os medicamentos.
    3- Confere os tipos de medicamentos.
    4- Confere a quantidade de cada medicamento.
    5- Cadastra os medicamentos no sistema.

Caso de uso "B":

    Ator: Dono

    Fluxo normal:
    1- Recolhe dados do novo funcionário.
    2- Abre o sistema de gerenciamento de funcionários e clica em cadastro.
    3- Preenche os campos com os dados do funcionário.
    
    Extensões:
    3.1- Se o dono não informar o CPF do funcionário, informar que o campo de CPF é obrigatório.
    3.2- Caso o CPF não seja válido, não permitir o cadastro e pedir para que insira um CPF válido.
    3.3- Se o CPF informado já estiver cadastrado no sistema, informar que o funcionário já existe.

Caso de uso "C":

    Ator: Dono

    Fluxo normal:
    1- Confere o setor do funcionário.
    2- Confere o cargo do funcionário.
    3- Confere se as horas esperadas no mês são equivalentes com a carga horária cadastrada pelo funcionário.
    4- Efetua o pagamento.
    
    Extensões:
    3.1- Caso as horas cadastradas não sejam equivalentes as horas esperadas no mês, pedir justificativa para a falta de horas.
    3.2- Se não houver justificativas, descontas as horas pedentes do salário do funcionário.
