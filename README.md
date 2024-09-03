Código Mermaid:
```
classDiagram
    Iphone -->ReprodutorMusical
    Iphone -->AparelhoTelefonico
    Iphone -->NavegadorInternet
    class ReprodutorMusical{
      +tocar()
      +pausar()
      +selecionarMusica(String musica)
    }
    class AparelhoTelefonico{
        +ligar(String numero)
        +aternder()
        +iniciarCorreioVoz()
    }
    class NavegadorInternet{
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }
```
