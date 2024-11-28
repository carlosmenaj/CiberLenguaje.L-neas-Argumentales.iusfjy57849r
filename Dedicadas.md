Son acciones que responden a una determinada especificación que define unos atributos o características particulares que son indispensables para que la misma se corresponda con el espacio donde ocurren. La acción requiere de una preparación para provocar un resultado a ser movilizado a otra argumentación recipiente.
| Columna 1                           | Columna 2     | Columna 3 |
|-------------------------------------|---------------|-----------|
| Parece ser que obliga a llenar      | Fila 1C2      | Fila 1C3  |
| Fila 2C1                            | Fila 2C2      | Fila 2C3  |

#!/bin/bash

# Archivo destino
OUTPUT_FILE="tabla.md"

# Cabecera de la tabla
echo "| Columna 1 | Columna 2 | Columna 3 |" > $OUTPUT_FILE
echo "|-----------|-----------|-----------|" >> $OUTPUT_FILE

# Añadir filas (ejemplo de un bucle)
for i in {1..5}; do
    echo "| Fila $iC1 | Fila $iC2 | Fila $iC3 |" >> $OUTPUT_FILE
done

echo "Tabla generada en $OUTPUT_FILE"
