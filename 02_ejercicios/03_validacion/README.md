# Ejercicio 3 - Validación

Indica si cada uno de los siguientes es un documento XML bien formado. Si no lo es, explica por qué, y qué se podría cambiar para conseguir que sí lo fuese.

## 1

```xml
<?xml version="1.0" encoding="UTF-8"?> 
<persona> 
  <nombre>Ion</nombre>
  <DNI>12784259L</DNI>
</persona>
<persona>
  <nombre>Miren</nombre>
  <DNI>51243021P</DNI> 
</persona>
```

## 2

```xml
<?xml version="1.0" encoding="ISO-8859-1"?>
<texto> Esto es un <negrita>texto</negrita> con formato. </texto> 
```

## 3

```xml
<?xml version="1.0" encoding="ISO-8859-1"?>
<texto> Esto es un <negrita><cursiva>texto</negrita> con más</cursiva> formato. </texto>
```

## 4

```xml
<coche>
  <marca>Peugeot</marca> 
	<modelo>308</modelo>
</coche> 
```

## 5

```xml
<?xml version="1.0" encoding="UTF-8"?>
<amigos>
 	<amigo direccion="Avenida Gasteiz"> Joseba Oribe</amigo>
 	<amigo direccion="Gran Via"> Leire Aguirre</amigo> 
</amigos>
```

## 6

```xml
<?xml version="1.0" encoding="UTF-8"?>
<amigos>
  <amigo telefono=999999999  telefono=666666666>Joseba Oribe</amigo>
  <amigo telefono=933333333>Leire Aguirre</amigo>
</amigos>
```
