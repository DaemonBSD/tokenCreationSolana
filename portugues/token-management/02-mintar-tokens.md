# Mintar Tokens

Depois de criar seu token, o próximo passo é mintar alguns tokens.

### Passo 1: Criar uma Conta de Token

Primeiro, crie uma conta de token onde seus tokens serão armazenados:

```bash
spl-token create-account <ENDERECO_DO_TOKEN>
```

Substitua `<ENDERECO_DO_TOKEN>` pelo endereço do token que você criou.

### Passo 2: Mintar Tokens

Agora, você pode mintar tokens para a conta de token criada:

```bash
spl-token mint <ENDERECO_DO_TOKEN> <QUANTIDADE> <CONTA_DO_TOKEN_DESTINATARIO>
```

Substitua `<ENDERECO_DO_TOKEN>`, `<QUANTIDADE>`, e `<CONTA_DO_TOKEN_DESTINATARIO>` com o endereço do seu token, a quantidade de tokens que você deseja mintar, e a conta de token que você criou, respectivamente.

### Passo 3: Verificar Mintagem

Para verificar se os tokens foram mintados, você pode verificar o saldo da conta de token do destinatário:

```bash
spl-token balance <CONTA_DO_TOKEN_DESTINATARIO>
```

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
