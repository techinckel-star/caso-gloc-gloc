# caso-gloc-gloc 
# Projeto Prático — Caso Jurídico com RAG

## Descrição

Projeto acadêmico individual destinado à demonstração de um fluxo de
tratamento de informações jurídicas utilizando dados fictícios,
sanitização, RAG com fontes limitadas, verificação, auditoria e revisão
humana.

O caso envolve uma solicitação fictícia de exclusão de dados pessoais
realizada por uma candidata a processo seletivo.

## Aviso

Todos os personagens, identificadores e acontecimentos específicos do caso
são fictícios.

O projeto não contém dados pessoais reais.

O material não constitui parecer jurídico.

## Objetivos

O projeto demonstra:

- criação de relato jurídico fictício;
- identificação de informações que não devem ser expostas;
- sanitização dos dados;
- seleção de fontes para RAG;
- restrição da consulta às fontes selecionadas;
- registro das afirmações;
- verificação das afirmações;
- auditoria;
- revisão humana;
- versionamento;
- documentação do fluxo.

## Estrutura

```text
entrada/
    relato_bruto.md

apoio/
    caso_sanitizado.md
    fonte_1.md
    fonte_2.md

docs/
    limites_e_sigilo.md
    especificacao.md
    prompts/
        consulta_rag.md
        auditoria.md

evidencias/
    resposta_inicial.md
    verificacao.md
    auditoria.md
    revisao_humana.md

entrega/
    orientacao_inicial.md