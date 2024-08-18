 # Challenge: Encriptador de textos
 ## Presentación
 <p>
   Hola a todos! Es un gusto presentarles mi proyecto llamado "Encriptador de Textos", el cual desarrollé 
   como parte del challenge final del programa de ORACLE y ALURA. 
   Este proyecto fue creado siguiendo los apuntes, guías y el apoyo p
   roporcionado por ALURA durante las clases. También utilicé ChatGPT para mejorar y optimizar mi código.
   <hr>
   
 </p>
<img src="https://github.com/user-attachments/assets/0f2f1edc-c838-4794-bad7-82789ff815ca" alt="Portada principal del encriptador" width="800" height="400" >

### Descripción de la aplicación
<p>
  La función principal de esta aplicacion es encriptar un texto ingresado por el usuario siguiendo unas condiciones establecidas acontinuación:
</p>

- El texto ingresado solo debe ser en minusculas
- Palabras sin acentos ni caracteres especiales
- La interfaz de usuario debe tener la facilidad de encriptar una palabra y desencriptarla.

#### Las "llaves" de encriptación son las siguientes:
```
La letra "a" es convertida para "ai"
La letra "e" es convertida para "enter"
La letra "i" es convertida para "imes"
La letra "o" es convertida para "ober"
La letra "u" es convertida para "ufat"

```
## Estructución de la logica del programa
<p>
  Para la estructura logica del programa utilicé "Pseudocodigo" y "Diagrama de flujo"
</p>

### Pseudocódigo
<p>
A continuación, presento el pseudocódigo que utilicé para guiarme y abstraer los elementos más esenciales del proyecto a traves de tres pasos fundamentales:
</P>

#### 1. Encriptar
1. Solicitar al usuario que ingrese el texto que desea encriptar.
2. Verificar si el texto ingresado cumple con las condiciones:
- Solo letras minúsculas.
- Sin acentos ni caracteres especiales.
3. Si se cumplen las condiciones, convertir el texto en texto encriptado.
4. Si no se cumplen las condiciones, solicitar nuevamente al usuario que ingrese un texto válido.

#### 2. Desencriptar
1. El texto encriptado, que puede ser guardado en una variable, solo requiere una entrada del usuario.
2. El usuario ingresa el texto encriptado.
3. Reemplazar la secuencia de caracteres encriptados por las vocales originales, utilizando un método dentro de una función.

#### 3. Copiar texto
1. Permitir al usuario copiar el texto que ha sido encriptado o desencriptado.
2. Copiar automáticamente la salida de texto (output) generada por las dos funciones anteriores al portapapeles.

<p>
  Ya con una definición mas simplificada, puedo tener una visión clara para saber que propiedades de JS (operadores logicos, comparación., ondicionales...) 
</p>

## Diagrama de flujo
<p>
  Acontinuación solo muestro la captura del diagrama del encriptador, para el desencriptador y copiar texto solo requiere remplazar
  las llaves por los carecteres originales del input.
  <hr>
</p>
<img src="https://github.com/user-attachments/assets/df1ef1e9-7b23-44ec-80ca-e7f589557180" alt="Portada principal del encriptador" width="800" height="400" >

 
