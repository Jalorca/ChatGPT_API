# ChatGPT_API
Este repositorio es para aprender a utilizar la API de CHATGPT.
## Miembros del equipo:
- Ordinola Castillo, Javier Alexander
- Ordinola Mondragon, Martín André
- Ipanaqué Sánchez, Cristhian Edward
- Ipanaqué Sánchez, Josemanuel Edward
- Rodríguez Masumura, Enrique Kiyoshi
## Creación de ambiente virtual
> La creación del ambiente virtual debe realizarse antes de ejecutar los ejemplos del Jupyter Notebook.
1. Ejecutar la siguiente línea de código en el terminal.
```
python -m venv venv
```
2. Ejecutar la siguiente línea de código en el terminal.
```
.\venv\Scripts\activate
```
Para verificar que se ha creado el ambiente virtual al lado izquierdo de la línea de terminal debera aparecer lo siguiente: **(venv)**, de la siguiente forma:
```
(venv) PS C:\Users\alexz\Documents\ChatGPT\ChatGPT_API>
```
> La ubicación del directorio local es a conveniencia.

> Si se presenta un error de seguridad es necesario activar los permisos desde PowerShell, lo cual se muestra en el siguiente apartado.
3. Ahora se puede proceder con la importación de la libreria OpenAI.
## Activación de los permisos en PowerShell
1. Ejecutar PowerShell como Administrador.
2. Ingresar lo siguiente en el terminal de PowerShell:
```
Get-ExecutionPolicy
```
3. Ingresar lo siguiente en el terminal de PowerShell:
```
Set-ExecutionPolicy RemoteSigned
```
4. Aparecerá un mensaje donde te pide la confirmación de activación de permisos, deberás escribir **S** para activar los permisos.
