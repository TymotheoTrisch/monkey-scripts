# monkey-scripts

Coleção de userscripts para **Violentmonkey** e otimizações de navegador para uso geral e no trabalho.

## Estrutura

```text
monkey-scripts/
├── README.md
├── CHANGELOG.md
└── scripts/
    ├── geral/       # Scripts e otimizações de uso geral
    └── secullum/    # Automações para sistemas Secullum
```

## Como instalar um script

1. Instale a extensão **Violentmonkey** no navegador (Firefox ou Chrome/Edge).
2. Abra o arquivo `.user.js` desejado aqui no GitHub e clique em **Raw**.
3. O Violentmonkey detectará o cabeçalho `==UserScript==` e abrirá a tela de confirmação para instalar.

## Padrão dos scripts

- Arquivos sempre com sufixo `.user.js` e nomes em `kebab-case`.
- Bloco `==UserScript==` atualizado com `@name`, `@namespace`, `@version`, `@description` e `@match` restrito aos domínios necessários.
- **Zero dados sensíveis:** nunca versionar senhas, tokens, CPFs ou dados de clientes.
