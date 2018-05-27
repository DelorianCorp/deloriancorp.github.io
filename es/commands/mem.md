# Comando ```mem```

El comando ```mem``` almacena los bytes indicados en la memoria EEPROM de el prototipo DC001M. Se usa con un punto y coma (;) al final y tiene 1 parámetro, este son los bytes que se desea almacenar en la memoria.

### Sintaxis:
```sh
mem Hola X2,;
```

### Ejemplo:
```sh
inicio:
mem Hola X3,;
fin;
```
