classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String selecionar)
    }

    class AparelhoTelefonico {
        +atender()
        +iniciarCorreioVoz()
        +ligar(String numero)
    }

    class NavegadorInternet {
        +adicionarNovaAba()
        +exibirPagina(String url)
        +atualizarPagina
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet

    
![image](https://github.com/julianaquachio/desafioiphoneuml/assets/166079880/770a6017-faee-4bca-a421-3b6049f8186e)

