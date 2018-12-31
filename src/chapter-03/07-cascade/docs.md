# Cascade

La cascada combina reglas de especifidad y herencia juntas para resolver estilos que tienen conflictos entre ellos.

## Cascade rules

- Encontrar todas las reglas que contiene un selector
- Clasificar todas las reglas por su peso !important
- Clasificar todas las reglas por su origen. Hay 3 orígenes posibles autor, lector y navegador.
- Clasificar todas las declaraciones por su especifidad.
- Clasificar todas las declaraciones por el orden en el que vienen.

### Order pseudoclases

Love && Focus && Hate

- :link
- :visited
- :focus
- :hover
- :active
