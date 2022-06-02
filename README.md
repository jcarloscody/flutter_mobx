# MOBx

## Dependências

- mobx
- flutter_mobx
- provider
- build_runner(dev) responsavel por gerar o código
- mobx_codegen(dev) responsavel por gerar o código

## Princípios

- Actions: ação.
- Observables: quem está sendo referenciado.
- Reactions: reação.

### Comando: flutter pub run build_runner --help

Ele gera um arquivo .g que tratará do padrão observer.

> Observer(builder: (_)=>widget)
