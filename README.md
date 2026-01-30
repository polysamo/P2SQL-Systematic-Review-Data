# Análise de Estudos Relacionados a Injeção de Prompt Direto em LLM no Contexto SQL

Este repositório contém o material suplementar relativo ao processo de triagem da revisão sistemática de literatura realizada no presente estudo.

## Conteúdo do Repositório
* `artigos_excluidos.xlsx`: Planilha detalhada contendo:
  * A lista dos 183 artigos identificados inicialmente.
  * O mapeamento dos 178 artigos que não foram selecionados.

## Motivos de Exclusão
1. **Fora do Escopo Temporal:** Publicações anteriores a 2020, não refletindo as vulnerabilidades atuais de agentes integrados.
2. **Tipo de Publicação:** Editoriais, resumos, capítulos de livros ou revisões já existentes.
3. **Foco em Injeção Indireta:** Estudos que abordavam envenenamento de dados externos em vez da instrução direta do usuário no chat.
4. **Falta de Componente SQL:** Pesquisas que tratavam de *Prompt Injection* genérico sem a tradução para comandos de banco de dados (*Prompt-to-SQL*).
5. **Metodologia Insuficiente:** Trabalhos sem detalhamento técnico que permitisse a reprodutibilidade dos ataques ou defesas e que não abordassem.

## Metodologia de Triagem
A triagem seguiu critérios rigorosos de inclusão e exclusão para focar especificamente na **Injeção de Prompt-to-SQL (P2SQL)**, um vetor de ataque onde prompts em linguagem natural são traduzidos em comandos SQL maliciosos. 

A escassez de estudos específicos nesta área é evidenciada pelo fato de que apenas 5 artigos atenderam integralmente aos requisitos de análise técnica de injeções diretas em aplicações integradas.
