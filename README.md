# Platzom

Platzom es un idioma inventado para el [curso de Fundamentos de JavaScript](https://platzi.com/js) de [platzi](https://platzi.com), el mejor lugar de educación online.

## Descripcion del idioma

- Si las palabras termina con "ar" se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
- Por último, si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas.

## Instalación
```
npm install platzom
```

## Uso
```
import platzom from 'platzom'

platzom("Programar") // Program
Platzom("Zorro") // Zorrope
Platzom("Zarpar") // Zarppe
Platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos
- [Sacha Lifszyc] (httpsp:// twitter.com/@slifszyc)
- [Richard] (richard_2929@outlook.com)

## Licencia

[MIT] (https://opensource.org/licenses/MIT)