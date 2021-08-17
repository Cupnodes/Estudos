# Position

## Static

- O elemento segue o fluxo natural da página

- Alocações (top | bottom | left | right) **não funcionam**

## Relative

- Segue o fluxo natural da página, mas **alocações funcionam**

## Absolute

- O elemento passa a **ignorar** o fluxo normal da página

- Caso o elemento tenha como pai alguém com `position: relative`, ele passa a usar o pai como referência.

## Fixed

- O elemento *não é afetado por scrolling*