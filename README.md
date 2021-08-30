# Prueba-gha
CI/CD with Githug Actions

# Acción de docker Hello world

Esta acción imprime "Hola Mundo" o "Hola" + el nombre de una persona a quien saludar en el registro.

## Entradas

### `who-to-greet`

**Obligatorio** El nombre de la persona a quien saludar. Default `"Mundo"`.

## Outputs

### `time`

El tiempo en que lo saludamos.

## Ejemplo de uso

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'