# Hello-js-action

## Introducción
---
Hello-js-action se trata de una acción de GitHub extremadamente simple, puesto que su único propósito es imprimir *"Hello World"* por la consola del sistema. El programa permite una entrada, siendo esta una **cadena**. Si se provee, el mensaje cambia a *"Hello (cadena)"*. 
Además de ello, la acción también notifica sobre la **fecha** en la que se realizó la impresión del saludo.

---
## Inputs
La acción permite una única entrada. Esta debe ser una cadena que indique aquello a lo que se quiere saludar. Su indicación, no obstante, es opcional. Si no se provee, el mensaje que se imprimirá por parte de la acción sera siempre *"Hello World"*.

---
## Outputs
La acción produce dos salidas distintas:
* El saludo generado.
* La fecha en la que se produjo el saludo.

---
### Ejemplo de uso
```yml
uses: actions/hello-js-action-alu0101100654@v1
with:
  who-to-greet: 'Alan Turing'
```