### COPIA DE ADLAI
## Tarea - Clase 03
**Nivel 13 - Flexbox Froggy**
Tarea - Clase 03
Nivel 13 - flexboxfroggy.com
#pond {
  display: flex;
justify-content: center;
align-items: flex-end;
flex-direction: row-reverse;
}

## Tarea - Clase 04
**Nivel 24 - Flexbox Froggy**
/* NIVEL 24 - FLEXBOX FROGGY*/
#pond {  
	display: flex;
	flex-flow: column-reverse wrap-reverse;
	align-content: space-between;
	justify-content: center;
	}

**Nivel 28 - CSS GRIDGARDEN**
#garden {
  display: grid;
grid-template: 1fr 50px / 20% 1fr;
}	

## Tarea - Clase 06
/*
Intermedia 2:
La respuesta es SI, por el beneficio, es decir un cambio, en un solo lugar. Si posteriormente se quisiera hacer un cambio en la tabla o quitar los bordes verticales, el cambio sería en una línea en .celda. Sin el componente, se tendría que editar 12 sitios.
Y No porque un componente con @apply es una capa de indirección más: quien lee el HTML ya no ve los estilos y tiene que ir a buscarlos.
*/