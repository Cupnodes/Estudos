# Em ou Rem
### Pixel
- Valor Fixo

- Como essa unidade tem tamanho fixo, ela pode gerar **problemas de acessibilidade** dependendo do tamanho da tela

### Em
- O tamanho da tipografia é relativo ao **tamanho da fonte**

`
p {
    font-size: 2em **(32px)**
}
`

- A desvantangem do *Em* é que ele é **acumulativo**, o que pode aumentar bastante a complexidade do site

### Rem
- Leva em consideração o tamanho da **fonte raíz** do site

`
html {
    font-size: 14px;
}

p {
    font-size: 10rem; **(140px)**
}
`

- O desenvolvimento do *Rem* começou em **2010**

**NOTA**: O tamanho padrão da fonte é 16px    