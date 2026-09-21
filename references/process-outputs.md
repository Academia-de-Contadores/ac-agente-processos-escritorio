# Saídas de processo

Leia somente o formato necessário. Todo artefato é uma primeira versão
revisável; campos sem evidência recebem `[A VALIDAR]`.

## `/mapa`

Entregue: nome, objetivo observável, gatilho, entradas, etapas numeradas,
responsáveis por função, dependências, evidências, riscos, exceções, SLA
informado, resultado e handoff. Uma etapa começa com verbo e termina com algo
observável.

## `/raci`

Use uma linha por etapa e as colunas `Etapa | R | A | C | I | Evidência`.
Não atribua nomes ou funções não informados. Marque `[A VALIDAR]` e explique a
decisão necessária. Não confunda `A` de accountable com autorização para agir.

## `/checklist`

Agrupe por preparação, execução, revisão, exceção e handoff. Cada item deve ter
responsável por função, dependência, evidência e estado. Evite listas soltas que
não mostram ordem ou critério de conclusão.

## `/plano-5-dias`

- Dia 1: observar a execução real e registrar lacunas.
- Dia 2: ordenar entradas, etapas, papéis e dependências.
- Dia 3: definir evidências, revisões, riscos e exceções.
- Dia 4: testar com cenário fictício ou anonimizado.
- Dia 5: ajustar ambiguidades e submeter a versão à aprovação humana.

Os dias são uma sequência de ativação do método, não promessa de implantação
nem SLA do processo.

## `/teste`

Registre executor por função, cenário anonimizado, entradas entregues, dúvidas,
ajudas solicitadas, evidências ausentes, resultado, prazo interno informado e
ajustes para a próxima versão.

## Exemplo compacto

Pedido: “Organize o recebimento mensal de documentos; ainda não definimos quem
cobra pendências nem o prazo.”

Saída correta: mapear o recebimento e as evidências já descritas; escrever
`Responsável pela cobrança: [A VALIDAR]` e `SLA: [A VALIDAR]`; entregar um
checklist revisável e perguntar quem decide esses dois campos. Não escolher a
função nem criar um prazo padrão.
