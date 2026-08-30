# Pasta de trabalho

Estrutura para organizar documentos, planilhas e apresentações.

## Como está organizada

```
00-entrada/           Caixa de entrada — arquivo novo entra por aqui
01-documentos/        Textos finalizados (.docx, .pdf, .md)
   contratos/           Contratos assinados e minutas
   propostas/           Propostas comerciais e orçamentos
   relatorios/          Relatórios, atas e memorandos
02-planilhas/         Planilhas de trabalho (.xlsx, .csv)
03-apresentacoes/     Slides (.pptx, .pdf)
04-dados-brutos/      Exportações de sistemas, sem edição
05-modelos/           Modelos em branco reutilizáveis
99-arquivo/           Material encerrado, guardado por ano
```

Os números na frente servem só para manter a ordem no explorador de arquivos.
Cada pasta tem um `LEIA-ME.md` explicando o que vai nela.

## As três regras

**1. Tudo entra por `00-entrada/`.** Baixou, recebeu, exportou: cai ali. Depois
você move para o lugar certo. Assim nunca há dúvida sobre onde largar um
arquivo na pressa.

**2. `00-entrada/` esvazia toda semana.** É o único ritual desta estrutura. Sem
ele, a caixa de entrada vira o depósito de sempre e a organização se desfaz.

**3. `04-dados-brutos/` é intocável.** O arquivo original nunca é editado. Toda
edição acontece sobre uma cópia, para que a análise sempre possa ser refeita
do zero.

## Nome dos arquivos

Data primeiro, no formato `AAAA-MM-DD`, para que a ordem alfabética já seja a
ordem cronológica:

```
2026-08-30_proposta_cliente-acme.pdf
2026-08_fechamento-mensal.xlsx
```

Sem espaços nem acentos no nome (use hífen), e versão no fim quando houver:
`_v2`, `_v3`. Planilha que é atualizada continuamente não leva data —
o nome descreve o conteúdo: `controle-de-caixa.xlsx`.

## Arquivar

O que passou de um ano sem uso vai para `99-arquivo/<ano>/`. Não se apaga:
sai da frente, mas continua encontrável.
