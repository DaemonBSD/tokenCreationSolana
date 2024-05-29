# Remover Todas as Autoridades

Para máxima segurança, você pode querer remover todas as autoridades do seu token. Isso tornará o token completamente imutável.

### Passo 1: Remover Autoridade de Mintagem

```bash
spl-token authorize <ENDERECO_DO_TOKEN> mint --disable
```

### Passo 2: Remover Autoridade de Congelamento

```bash
spl-token authorize <ENDERECO_DO_TOKEN> freeze --disable
```

### Passo 3: Remover Autoridade do Proprietário da Conta

```bash
spl-token authorize <ENDERECO_DO_TOKEN> owner --disable
```

### Passo 4: Remover Autoridade de Fechamento

```bash
spl-token authorize <ENDERECO_DO_TOKEN> close --disable
```

### Verificar Remoção das Autoridades

Para verificar a remoção das autoridades, você pode verificar os detalhes do token:

```bash
spl-token token-info <ENDERECO_DO_TOKEN>
```

[Voltar para a pagina anterior](../README.md)

_Created by [DaemonBSD](https://x.com/DaemonB2D)_
