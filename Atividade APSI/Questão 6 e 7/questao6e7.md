### 6- Identifique as classes, atributos e métodos desses cenários e coloque em uma tabela.
### 7- Desenha o diagrama de classes UML. Leve em consideração os relacionamentos vistos em sala.
``` Mermaid
classDiagram
    class Cliente {
        -String nome_cliente
        -Int cod_cliente
        Animal.get_codAnimal() :int
        +get_nomeCliente() :String
        +get_codCliente()  :int
        +set_nomeCliente()
        +set_codCliente()
    }
    class Funcionário {
        -String nome_funcionario
        -Int horas_trabalhadas
        -Const horas_esperadas
        -Int cod_funcionario
        -Int falta_horas
        +get_nomeFuncionario() :String
        +get_codFuncionario() :String
        +set_nomeFuncionario()
        +set_codFuncionario()
        +set_horasTrabalhadas(this.horas_trabalhadas + horas_trabalhadas)
        +carga_horária(cod_funcionario,horas_trabalhadas,horas_esperadas) :String nome_funcionario + Int falta_horas
    }
    class Animal {
        -String nome_animal
        -Int idade_animal
        -String sex_animal
        +Int cod_animal
        +get_nomeAnimal()   :String
        +get_idadeAnimal()  :int
        +get_sexAnimal()    :String
        +get_codAnimal()    :int
        +set_nomeAnimal()
        +set_idadeAnimal()
        +set_sexAnimal()
        +set_codAnimal()
    }   
    class Medicamento {
        -Int cod_medicamento
        -String nome_medicamento
        -Int qnt_medicamento
        +get_codMedicamento()  :int
        +get_nomeMedicamento() :String
        +get_qntMedicamento() :int
        +set_codMedicamento()
        +set_nomeMedicamento()
        +set_qntMedicamento()
    }
    class Consulta {
        -Date data_consulta
        Funcionario.get_codFuncionário() :int
        Animal.get_codAnimal() :int
        Cliente.get_codCliente() :int
        Medicamento.get_codMedicamento() :int
        Medicamento.get_nomeMedicamento() :String
    }
Cliente "1"<.."1..*"        Animal   :Depende
Cliente "1"-->"1..*"           Consulta :Participa
Animal "1"-->"1..*"         Consulta :Possui
Funcionário "1..*"-->"*"    Consulta :Participa
Medicamento "1..*"-->"*"      Consulta :Participa
```