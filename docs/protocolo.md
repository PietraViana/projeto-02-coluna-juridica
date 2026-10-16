# Protocolo de produção da coluna

## Objetivo

Converter o briefing do advogado em um rascunho completo, organizado, legível e adequado ao padrão editorial disponível. O rascunho é sempre submetido ao advogado autor; este fluxo não aprova tese jurídica nem envia conteúdo à revista.

## Etapas

1. **Ler a entrada.** Identificar tema, narrativa, objetivo, público, limite de caracteres, fontes e restrições. Se faltar um dado essencial, não inventar: destacar a lacuna no rascunho ou pedir complemento quando ela impedir a redação.
2. **Definir o roteiro.** Antes de redigir, organizar: título; introdução com a questão e sua relevância; desenvolvimento com a explicação jurídica; exemplo/narrativa; conclusão que retome o objetivo e indique a reflexão ou decisão esperada.
3. **Redigir.** Preparar texto coeso e completo, usando apenas os fatos e referências fornecidos ou verificáveis. Distinguir regra jurídica, interpretação e opinião do autor. Não criar citações, precedentes, números de processo ou fatos.
4. **Aplicar o estilo.** Usar o guia em `apoio/guia_estilo_revista.md` e, quando disponíveis e pertinentes, os exemplos em `apoio/colunas_anteriorer_exemplo.md`. Instruções específicas do autor prevalecem sobre preferências editoriais provisórias, sem afastar as exceções deste protocolo.
5. **Conferir extensão e estrutura.** Contar caracteres do corpo e do texto completo, incluindo espaços; declarar qual contagem foi usada. Comparar com o teto informado. Se o teto não estiver disponível, registrar “limite não informado” e não afirmar conformidade.
6. **Revisar e salvar.** Corrigir ortografia, concordância, pontuação, repetição e consistência de termos. Salvar em `saída/rascunhos/AAAA-MM-DD-titulo.md` e atualizar `docs/registro.md`.
7. **Revisão responsável.** O advogado autor confere precisão jurídica, tese, fontes, fatos, identificação de pessoas, adequação editorial e cortes sugeridos antes de qualquer envio à redação.

## Estrutura de saída

O arquivo começa com estado da revisão e contagem, seguido pelas seções abaixo. A contagem informativa não faz parte do texto da coluna.

```text
Estado: Rascunho para revisão do advogado
Caracteres: corpo = N (com espaços); total = N (com espaços; inclui título e subtítulos)
Limite informado: N / não informado
Pendências: nenhuma / lista

# Título

## Introdução
## Desenvolvimento
## Exemplo
## Conclusão
```

As seções podem receber títulos editoriais mais naturais; preserve a progressão e a função de cada parte. Se a narrativa estiver integrada ao desenvolvimento, não force uma repetição: mantenha a seção “Exemplo” apenas quando ela ajudar a leitura.

## Exceções e sinalizações obrigatórias

- **Tese controvertida:** não apresentar interpretação jurídica controvertida como consenso ou fato incontroverso. Sinalizar para o autor; se for mantida, identificá-la claramente como posição/opinião do autor e indicar a base informada. Não decidir a controvérsia em nome dele.
- **Caso identificável:** sinalizar qualquer detalhe que possa identificar pessoa, cliente, empresa ou processo. Não publicar nem ampliar os dados identificadores; solicitar confirmação de autorização/anonimização ao advogado.
- **Limite excedido:** informar contagem e excesso em caracteres, apontar trechos candidatos a corte e aguardar decisão editorial do autor sobre o que preservar. Não cortar argumento ou ressalva jurídica essencial silenciosamente.
- **Limite ausente:** informar a contagem obtida e marcar que a conformidade não pode ser confirmada até a revista informar o teto e o critério de contagem.
- **Fonte/fato não confirmado:** marcar a afirmação para conferência. Não inventar referência nem substituir fonte sem registrar a alteração.
- **Entrada insuficiente ou conflitante:** marcar a pergunta concreta e evitar preencher a lacuna com fatos ou intenção presumidos.

## Lista de conferência

- [ ] O texto cumpre o objetivo declarado na entrada.
- [ ] Título e progressão estão claros; introdução, desenvolvimento, exemplo e conclusão têm função reconhecível.
- [ ] Afirmações jurídicas e fontes correspondem ao material fornecido e estão distinguidas de opinião.
- [ ] Nenhum fato, autoridade ou citação foi inventado.
- [ ] Casos potencialmente identificáveis estão sinalizados.
- [ ] Guia de estilo e extensão foram conferidos; limite ausente/excedido está explícito.
- [ ] O arquivo está marcado como rascunho e aguarda revisão do advogado autor.
