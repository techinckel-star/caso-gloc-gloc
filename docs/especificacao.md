# Especificação do fluxo

## Objetivo

Demonstrar um fluxo controlado de análise de um relato jurídico fictício
utilizando RAG com fontes previamente selecionadas.

## Entrada

O sistema recebe:

1. relato bruto;
2. versão sanitizada;
3. conjunto limitado de fontes.

## Recuperação

O RAG deve consultar somente:

- Fonte 1 — Constituição Federal;
- Fonte 2 — LGPD.

## Restrições

Não utilizar fontes externas que não estejam registradas em `apoio/`.

Não inventar dispositivos legais.

Não criar citações inexistentes.

Quando a fonte não permitir confirmar uma afirmação, registrar a limitação.

## Saída

A resposta deve apresentar:

1. fatos considerados;
2. questões identificadas;
3. fundamentos encontrados nas fontes;
4. pontos não confirmados;
5. orientação inicial;
6. necessidade de revisão humana.

## Cadeia de evidências

Toda afirmação jurídica relevante deve possuir:

- afirmação;
- fonte;
- localização da fonte;
- resultado da verificação.

## Auditoria

A auditoria deve verificar:

- se a fonte utilizada estava autorizada;
- se a afirmação pode ser encontrada na fonte;
- se houve extrapolação;
- se houve informação inventada;
- se o caso permaneceu sanitizado.