# Alterar Configurações do Token

Você pode querer atualizar as configurações do seu token, como congelar uma conta ou definir uma nova autoridade.

### Congelar uma Conta

Congelar uma conta impede quaisquer transações futuras envolvendo esta conta:

```bash
spl-token freeze <CONTA_DO_TOKEN> <ENDERECO_DO_TOKEN>
```

Substitua `<CONTA_DO_TOKEN>` e `<ENDERECO_DO_TOKEN>` pelos respectivos endereços.

### Definir Nova Autoridade

Para definir uma nova autoridade (por exemplo, autoridade de mintagem ou autoridade de congelamento), use o seguinte comando:

```bash
spl-token authorize <ENDERECO_DO_TOKEN> <TIPO_DE_AUTORIDADE> <NOVA_AUTORIDADE>
```

Substitua `<ENDERECO_DO_TOKEN>`, `<TIPO_DE_AUTORIDADE>`, e `<NOVA_AUTORIDADE>` com o endereço do seu token, o tipo de autoridade (mint, freeze, etc.), e o novo endereço da autoridade.

### Verificar Alterações

Para verificar as alterações, você pode verificar os detalhes da conta de token:

```bash
spl-token account-info <CONTA_DO_TOKEN>
```

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
