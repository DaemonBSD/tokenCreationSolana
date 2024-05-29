# Instalar Rust e Cargo

Rust e Cargo são necessários para instalar o SPL Token CLI.

### Passo 1: Instalar Rust

Execute o seguinte comando para instalar o Rust:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Siga as instruções na tela para completar a instalação.

### Passo 2: Configurar Seu Ambiente

Após a instalação, configure seu shell atual:

```bash
source $HOME/.cargo/env
```

### Passo 3: Verificar Instalação

Para verificar se o Rust e o Cargo foram instalados corretamente, execute:

```bash
rustc --version
cargo --version
```

Você deve ver os números das versões do Rust e Cargo.

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
