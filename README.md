# Tech Human Pipeline

Distribuidor publico GitHub Pages de `pipeline.techhuman.com.br`.

O conteudo fonte nao mora neste repositorio. O workflow busca a fonte canonica em:

```text
TECH-HUMAN/th-new-business-model/09-pipeline-site
```

## Regra de seguranca

Este site e publico-seguro. Ele nao deve conter nomes reais de prospects, contatos, valores,
propostas individuais, historico de negociacao ou logs sensiveis dos AGENTS SDR IA.

Dados reais pertencem ao CRM proprio Tech Human.

## Deploy

O deploy roda automaticamente quando este repositorio recebe push em `main`, por acionamento manual
ou pela agenda do workflow.

O segredo necessario e:

```text
TH_NEW_BUSINESS_MODEL_READ_TOKEN
```

## DNS

Registro esperado na Hostinger:

```text
Tipo: CNAME
Nome: pipeline
Aponta para: tech-human.github.io
TTL: 3600
```
