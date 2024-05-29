# Tornar Tokens Imutáveis

Para garantir a imutabilidade dos seus tokens, você precisa desativar a autoridade. Este passo é crucial para segurança e confiança.

### Passo 1: Desativar Autoridade de Mintagem

```bash
spl-token authorize <ENDERECO_DO_TOKEN> mint --disable
```

### Passo 2: Desativar Autoridade de Congelamento (se aplicável)

```bash
spl-token authorize <ENDERECO_DO_TOKEN> freeze --disable
```

Após executar esses comandos, ninguém poderá mintar novos tokens ou congelar contas.

### Verificar Imutabilidade

Para verificar se o token é imutável, você pode verificar os detalhes do token:

```bash
spl-token token-info <ENDERECO_DO_TOKEN>
```

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
