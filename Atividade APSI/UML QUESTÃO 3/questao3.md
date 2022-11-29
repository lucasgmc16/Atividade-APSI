``` Mermaid
    classDiagram
        class Anuncios{
        - Date dataAnuncio
        - Float valor
        - String titulo
        - String contato
        - String telefone
        - String telefone2
        - String observacao
        + get_observacao() String
        + get_valor() Float
        + get_dataAnuncio() Date
        - Secao.get_secaoProduto()
        + cadastrar(valor, titulo, contato, telefone, telefone2, observacao)
        }
        class Cliente{
            - String nome
            - String email
            - Int anunciante
            + get_anunciante() Int
            + set_anunciante()
            + cadastroCliente(email, nome)
            + assinarSecao(Secao)
        }
        class TipoAnuncio{
            - Enum tipo
            - Int quantidadePalavra
            - URL imagem
            - boolean temImagem
            + temImagem() boolean
            + get_imagem() URL
            + set_imagem()
            + set_tipo()
        }
        class Secao{
            - Enum secaoProduto
            + get_secaoProduto() Enum
            + set_secaoProduto()
            + enviarEmail()
        }
    Anuncios -->"1" TipoAnuncio
    Anuncios -- Cliente
    Anuncios -->"1..*" Secao
    Secao "0..*"<-->"0..*" Cliente
```