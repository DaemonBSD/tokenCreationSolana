# Instalar Solana CLI

A Interface de Linha de Comando (CLI) do Solana é necessária para interagir com a blockchain Solana.

### Passo 1: Baixar e Instalar

Abra seu terminal e execute o seguinte comando:

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```

### Passo 2: Atualizar o Caminho

Após a instalação, você precisa atualizar a variável de ambiente PATH para incluir o Solana CLI. Adicione a seguinte linha ao seu arquivo `.bashrc`, `.zshrc` ou equivalente:

```bash
export PATH="/home/seuusuario/.local/share/solana/install/active_release/bin:$PATH"
```

Depois, recarregue sua configuração de shell:

```bash
source ~/.bashrc
# ou
source ~/.zshrc
```

### Passo 3: Verificar Instalação

Para verificar se o Solana CLI foi instalado corretamente, execute:

```bash
solana --version
```

Você deve ver o número da versão do Solana CLI.

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
