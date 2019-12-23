# Emacs Bootcamp

Emacs Military Training Program.

Examples for the tutorial - [Doom Presents: Emacs Bootcamp](https://geekl0g.wordpress.com/tag/emacs-bootcamp/).

## Movement

C-n => Move the point down one line.

C-p => Move the point up one line.

C-e => Go the end of the line.

C-a => Go to the beggining of the line.

C-f => Move the point one character right.

C-b => Move the point one character left.

M-m => Move the point to the first non-space character on line.

C-l => Center the view.

C-x C-c => Exit Emacs.

C-d => Delete the character under the point.

C-x u => Undo the last action.

C-x C-s => Save the current buffer to disk.

C-x C-f => Opens a file by using a file path.

C-x C-k => Kills (closes) a buffer.

C-x b type buffer name RET => Create a new buffer.

C-x b => Move between buffers.

C-x C-b => List all open buffers.

C-x o => Jump to the other window.

C-x 1 => Displays only the current window.

C-x 0 => Displays the other window only.

C-x 2 => Splits the current window horizontally.

C-x 3 => Divide the current window vertically.

M-f => Move one word forward.

M-b => Move one word backward.

C-M-f => Move forward on a balanced expression.

C-M-b => Move backward on a balanced expression.

M-} => Jump to the next paragraph.

M-{ => Jump to the previous paragraph.

C-v => Move one screen down.

M-v => Move one screen up.

M-> => Move to the end of the buffer.

M-less than => Move to the beggining of the buffer.

M-g g => Go to line number.

C-M-v => Scroll the other window down.

C-M-S-v => Scroll the other window up.

C-SPC => Set the mark at the point.

C-x C-x => Exchange the point and the mark.

M-@ => Select next word.

C-u # => Pass the universal argument.

M-h => Select next paragraph.

C-x h => Mark all the buffer.

C-x r m => Set a bookmark.

C-x r l => Show the list of bookmarks.

C-x r b => Jump to a bookmark.

M-x bookmark-delete => Delets a bookmark.

C-x r SPC => Store the point position on a register.

C-x r j Cont to three => List all register.

C-x r j => Jump to a register.

C-s => Start the incremental search.

C-r => Start the incremental reverse search.

C-M-s => Start the incremental search by regular expression.

C-M-r => Start the incremental search by regular expression backward.

M-x occur RET => Start the occur mode.

M-x multi-occur-in-matching-buffers => Start the multi-occur search.

### Occur Mode Commands

The following list of commands must be executed inside an Occur Mode buffer:

M-n => Move to the next occur match.

M-p => Move to the previous occur match.

Greather than => Jump to the end of the occur buffer.

< => Jump to the beggining of the occur buffer.

g => Refresh the occur mode search.

e => Enable the occur editor mode.

q => Quit the occur mode.

## Editing

C-h C-h => Display the help menu.

C-h => Display the help menu.

C-d => Deletes the character under the point.

BACKSPACE => Deletes the previous character.

C-j => Adds a newline and moves the point to the new created line.

C-o => Adds a newline and maintains the point on the original line.

C-x C-o => Deletes the next blank lines.

M-d => Kills the next word.

C-BACKSPACE => Kills the previous word.

C-k => Kills the text from the position where the point is to the end of the
same line.

M-k => Kills the text from the position where the point is to the end of the
sentence.

C-M-k => Kills the next balanced syntactic expression.

C-S-BACKSPACE => Mata la línea actual.

C-y => Yanks text.

M-y => Cycle the kill ring entries.

C-M-w => Append to the kill ring current entry.

M-w => Copy the active region.

C-w => Cut the active region.

C-t => Transpose the character under the pont with the previous one.

M-t => Tranpose the word under the point with the previous one.

C-x C-t => Transpose the current line with the previous one.

M-q => Fill the paragraph.

C-S-e => Select the region from the point ot the end of the line.

C-S-a => Select the region from the point to the beggining of the line.

M-; => Comment or uncomment.

C-x C-; => Comment or uncomment the current line.

M-u => Change next word to uppercase.

M-l => Chage next word to lowercase.

M-c => Capitalize next word.

M-x cou-w => Count the number of words in the buffer.

OR

M-x count-words

M-x cou-w-r => Count the number of word in the selected region.

OR

M-x count-words-region

C-x l => Count the number of lines in the buffer.

M-a => Go to the beggining of the current line or to the beggining of the
previous line if your are at the beginning of the current.

M-e => Go to the end of the current line or to the end of the next line
if you are at the end of the current line.

TAB => Indent the current line.

M-C-\ => Indent a region.

C-x TAB => Manually indent as a block of text.

M-z => Zap, kills the text from the point to an arbitrary character.

M-x so-l => Order lines alphabetically.

OR

M-x sort-lines

M-x so-f => Order lines lexicographically.

OR

M-x sort-fields

M-x so-n => Order lines numerically.

OR

M-x sort-numeric

M-x rev-r => Reverse the ordering.

OR

M-x reverse-region

M-x so-c => Order by column.

OR

M-x sort-columns

M-/ => Expand the word in the buffer before the point as a dynamic abbrev.

C-M-/ => Complete the word before the point as a dynamic abbrev.

M-% => Interactive find/replace on active region, or from the position of
       the point to the end of the buffer if there is no active region.

C-M-% => Interactive find/replace with regexp, on the active region or from
         the position of the point to the end of the buffer if there is
         no active region.

M-x d-du => Delete all duplicate lines.

OR

M-x delete-duplicate-lines

M-x flu => Flush all lines that matchs with a regular expression.

OR

M-x flush-lines

M-x kee => Keep only the lines that matches a regular expression.

OR

M-x keep-lines

M-x hip => Expand words using hippie-expand.

OR

M-x hippie-expand

M-$ => Verify spell of the word before the point.

M-x isp-r => Verify the ortographical errors on the active region.

OR

M-x ispell-region

M-x flys-m => Flyspell minor mode that highlights ortographical errors.

OR

M-x flyspell-mode

M-x l-pac => List all available MELPA packages.

OR

M-x list-packages

M-x p-ins RET package-name RET => Installs a package.

OR

M-x package-install


## Special Commands

C-x C-f => Find a file.

C-x C-r => Find a file as read-only.

C-x C-q => Toggle read-only.

M-x kee => Keep only lines that matches a regular expression.

M-s o => List only lines that matches a regular expression.

M-s h p => Highlight a phrase.

M-s h r => Highlight by a regular expression.

M-s h . => Highlight the symbol under the point.

M-s h u => Undo the higlighting under the point.

M-x term => Opens a 'term' terminal buffer.

M-x shell => Opens a 'shell' terminal buffer.

M-x eshell => Opens a 'eshell' terminal buffer.

M-x eww => Opens EWW web browser.

M-x a-re-m => Refresh the buffer when the file is changed.

OR

M-x auto-revert-mode

C-x d => Starts Dired.

C-x C-f /ssh:user@remotehost:/file.txt => Starts TRAMP connection.


### 'term' Commands

C-c C-j => Enables term-line-mode.

C-c C-k => Enables term-char-mode.


### EWW Commands

M-<RET> => Opens the URL under the point on a new buffer.

b => Save bookmark.

B => List all bookmarks.

d => Download the URL under the point.

g => Reload the page.

S => List all open EWW buffers.

w => Copy the current URL to the kill ring.

M-C (Capital C and not Control) => Toggle colors.


### Dired Commands

plus sign => Create a new directory.

m => Marks a file or directory.

u => Unmarks a file or directory.

U => Unmarks everything.

C => Copy the marked items.

d => Set delete flag.

D => Deletes marked items.

x => Deletes flagged items.

*m => Marks a region.

*u => Unmarks the region.

*% => Marks files whose name matches with a regular expression.

*t => Toggle mark.

*c => Changes the mark symbol from the old to a new one.

g => Refresh the Dired buffer.

R => Renames the marked items.

O => Executes chown on the marked items.

G => Executes chgrp on the marked items.

M => Executes chmod on the marked items.

D => Deletes the marked items.

F => Visit the marked items. This command REQUIRES 'dired-x'.


### On a Help Menu Buffer

SPC => Scroll down the help menu.

DEL => Scroll up the help menu.

c => Show the command that a keybinding executes
                       (by typing a command name).

a => Apropos function, show information about a topic (i.e.: by
             typing a command name).

k => Show documentation that describes a command (by typing
               a command keybinding).

q => Quits the help menu.


### On a Find and Replace Buffer

y => Change the current search match (say yes) and move to the next.

n => Don't change the current match (say no) and move to the next.

! => Change all matches found (say yes to all).

q => Quit the find-and-replace.


### When Flyspell Mode is enabled

C-M-i => Autocorrect the word before the point.




# Campo de entrenamiento de Emacs

Programa de entrenamiento militar para Emacs.

Ejemplos para el tutorial - [Doom Presenta: Emacs Bootcamp](https://geekl0g.wordpress.com/tag/emacs-bootcamp/).


## Movimiento

C-n => Mueve el punto una línea abajo.

C-p => Mueve el punto una línea arriba.

C-e => Ir al final de la línea.

C-a => Ir al inicio de la línea.

C-f => Mover el punto un caracter a la derecha.

C-b => Mover el punto un caracter a la izquierda.

M-m => Mover el punto al primer caracter no-espacio de la línea.

C-l => Centrar la vista.

C-x C-c => Salir de Emacs.

C-d => Borrar el caracter bajo el punto.

C-x u => Deshacer la última acción.

C-x C-s => Salvar el buffer actual al disco.

C-x C-f => Abre un archivo usando una ruta de archivo.

C-x C-k => Mata (cierra) el buffer.

C-x b escriba el nombre del buffer RET => Crea un nuevo buffer.

C-x b => Moverse entre buffers.

C-x C-b => Listar todos los buffers abiertos.

C-x o => Saltar a la otra ventana.

C-x 1 => Despliega únicamente la ventana actual.

C-x 0 => Despliega únicamente la otra ventana.

C-x 2 => Divide la ventana actual horizontalmente.

C-x 3 => Divide la ventana actual verticalmente.

M-f => Moverse una palabra hacia adelante.

M-b => Moverse una palabra hacia atrás.

C-M-f => Moverse hacia adelante en una expresión balanceada.

C-M-b => Moverse hacia atrás en una expresión balanceada.

M-} => Saltar al próximo párrafo.

M-{ => Saltar al párrafo previo.

C-v => Moverse una pantalla abajo.

M-v => Moverse una pantalla arriba.

M-> => Moverse al final del buffer.

M-Menor que => Moverse al principio del buffer.

M-g g => Ir a la línea número.

C-M-v => Hacer scroll hacia abajo en la otra ventana.

C-M-S-v => Hacer scroll hacia arriba en la otra ventana.

C-SPC => Poner la marca en el punto.

C-x C-x => Intercambiar el punto y la marca.

M-@ => Seleccionar la próxima palabra.

C-u # => Pasar el argumento universal.

M-h => Seleccionar el próximo párrafo.

C-x h => Marcar todo el buffer.

C-x r m => Poner un bookmark.

C-x r l => Mostrar la lista de bookmarks.

C-x r b => Saltar a un bookmark.

M-x bookmark-delete => Borrar un bookmark.

C-x r SPC => Guardar la posición del punto en un registro.

C-x r j Contar hasta tres => Listar todos los registros.

C-x r j => Saltar a un registro.

C-s => Iniciar la búsqueda incremental.

C-r => Iniciar la búsqueda incremental reversa.

C-M-s => Iniciar la búsqueda incremental por expresión regular.

C-M-r => Iniciar la búsqueda incremental por expresión regular reversa.

M-x occur RET => Iniciar el modo occur.

M-x multi-occur-in-matching-buffers => Iniciar la búqueda multi-occur.

### Comandos del Modo Occur

La siguiente lista de comandos debe ejecutar dentro de un buffer en modo
Occur:

M-n => Moverse a la próxima coincidencia de occur.

M-p => Moverse a la coincidencia previa de occur.

Mayor que => Saltar al final del buffer occur.

< => Saltar al inicio del buffer occur.

g => Refrescar la búsqueda occur.

e => Habilitar el modo editor de occur.

q => Salir del modo occur.

## Edición

C-h C-h => Muestra el menú de ayuda.

C-h => Muestra el menú de ayuda.

C-d => Borra el caracter bajo el punto.

BACKSPACE => Borra el caracter previo.

C-j => Agrega una nueva línea y mueve le punto a la nueva línea.

C-o => Agrega una nueva línea y mantiene el punto en la línea original.

C-x C-o => Borra las próximas líneas en blanco.

M-d => Mata la próxima palabra.

C-BACKSPACE => Mata la palabra previa.

C-k => Mata el texto desde la posición adonde está el punto hasta el final
       de la misma línea.

M-k => Mata el texto desde la posición adonde está el punto hasta el final
       de la oración.

C-M-k => Mata la próxima expresión sintáctica balanceada.

C-S-BACKSPACE => Mata la línea actual.

C-y => Pega texto.

M-y => Cicla en el anillo kill.

C-M-w => Agrega a la entrada actual del anillo kill.

M-w => Copia la región activa.

C-w => Corta la región activa.

C-t => Transpone el caracter bajo el punto con el anterior.

M-t => Transpone la palabra bajo el punto con la anterior.

C-x C-t => Transpone la línea actual con la previa.

M-q => Llena el párrafo.

C-S-e => Selecciona la región desde el punto hasta el final de la línea.

C-S-a => Selecciona la región desde el punto hata el inicio de la línea.

M-; => Comenta o descomenta.

C-x C-; => Comenta o descomenta la línea actual.

M-u => Cambia la próxima palabra a mayúscula.

M-l => Cambia la próxima palabra a minúscula.

M-c => Capitaliza la próxima palabra.

M-x cou-w => Cuenta el número de palabras en el buffer.

Ó

M-x count-words

M-x cou-w-r => Cuenta el número de palabras en al región seleccionada.

Ó

M-x count-words-region

C-x l => Cuenta el número de líneas en el buffer.

M-a => Vaya al principio de la línea actual o al principio de la línea
       previa si ya estás al principio de la actual.

M-e => Vaya al final de la línea actual o al final de la próxima línea
       si ya estás al final de la línea actual.

TAB => Indenta la línea actual

M-C-\ => Indenta una región.

C-x TAB => Indentar manualmente como un bloque de texto.

M-z => Zap, mata el texto desde la posición del punto hasta un caracter
       arbitrario.

M-x so-l => Ordena líneas alfabéticamente.

Ó

M-x sort-lines

M-x so-f => Ordena líneas lexicográficamente.

Ó

M-x sort-fields

M-x so-n => Ordena líneas numéricamente.

Ó

M-x sort-numeric

M-x rev-r => Reversa el ordenamiento.

Ó

M-x reverse-region

M-x so-c => Ordena por columna.

Ó

M-x sort-column

M-/ => Expande la palabra antes del punto como un abbrev dinámico (DAbbrev).

C-M-/ => Completa la palabra antes del punto como un abbrev dinámico.

M-% => Búsqueda y reemplazo interactivo en al region activa, o desde la
       posición del punto hasta el final del buffer si no existe región
       activa.

C-M-% => Búsqueda y reemplazo interactivo usando una expresión regular
         en la región activa o desde la posición del punto hasta el final
         del buffer si no existe una región activa.

M-x d-du => Borra todas las líneas duplicadas.

Ó
M-x delete-duplicate-lines

M-x flu => Borra todas las líneas que coinciden con una expresión regular.

Ó

M-x flush-lines

M-x kee => Mantiene solamente las líneas que coinciden con una expresión
           regular.

Ó

M-x keep-lines

M-x hip => Expande palabras usando hippie-expand.

Ó

M-x hippie-expand

M-$ => Verifica la ortografía de la palabra antes del punto.

M-x isp-r => Verifica los errores ortográficos en las región activa.

Ó

M-x ispell-region

M-x flys-m => Modo menor flyspell que resalta los errores ortográficos.

Ó

M-x flyspell-mode

M-x l-pac => Lista todos los paquetes MELPA disponibles.

Ó

M-x list-packages

M-x p-ins RET nombre-paquete RET => Instala un paquete.

Ó

M-x package-install


### En un buffer de Menú de Ayuda

SPC => Hacer scroll hacia abajo en el menú de ayuda.

DEL => Hacer scroll hacia arriba en el menú de ayuda.

c => Muestra el comando que un teclazo ejecuta (digitando
     el nombre de un comando).

a => Función apropos, muestra información sobre un tópico (ej: al
      digitar el nombre de un comando).

k => Muestra documentación que describe un comando (al digitar
     un teclazo).

q => Quita el menú de ayuda.


### En un buffer de Búsqueda y Reemplazo

y => Cambie la coincidencia de búsqueda actual (decir sí) y moverse a la
     próxima.

n => No cambie la coincidencia actual (diga no) y muévase a la siguiente.

! => Cambie todas las coincidencias que encuentre (decir sí a todo).

q => Quitar la búsqueda y reemplazo.


### Cuando el Modo Flyspell está habilitado

C-M-i => Auto-corregir la palabra antes del punto.


## Teclazos Especiales

La lista de todos los teclazos usados en las misiones especiales se
muestra a continuación.

### Teclazos de Emacs

C-x C-f => Encontrar un archivo.

C-x C-r => Encontrar un archivo como solo lectura.

C-x C-q => Habilitar/Deshabilitar read-only.

M-x kee => Mantener solamente las líneas que coinciden con una expresión
           regular

M-s o => Listar solamente las líneas que coinciden con una expresión
         regular.

M-s h p => Resaltar una frase.

M-s h r => Resaltar usando una expresión regular.

M-s h . => Resaltar el símbolo bajo el punto.

M-s h u => Deshacer el resaltado bajo el punto.

M-x term => Abre un buffer 'term' de terminal.

M-x shell => Abre un buffer 'shell' de terminal.

M-x eshell => Abre un buffer 'eshell' de terminal.

M-x eww => Abre el navegador web EWW.

M-x a-re-m => Refresca el buffer cuando el archivo cambió.

OR

M-x auto-revert-mode

C-x d => Inicia Dired.

C-x C-f /ssh:user@remotehost:/file.txt => Inicia una conexión TRAMP.


### Teclazos de 'term'

C-c C-j => Habilita el modo term-line-mode.

C-c C-k => Habilitar el modo term-char-mode.


### Teclazos de EWW

M-<RET> => Abre el URL bajo el punto en un nuevo buffer.

b => Guarde el marcador (bookmark).

B => Listar todos los marcadores.

d => Descargar el URL bajo el punto.

g => Recargar la página.

S => Listar todos los buffers EWW abiertos.

w => Copiar el URL actual al anillo kill.

M-C (Capital C and not Control) => Habilitar/Deshabilitar los colores.


### Teclazos de Dired

símbolo de más => Crear un nuevo directorio.

m => Marcar un archivo o directorio.

u => Desmarcar un archivo o directorio.

U => Desmarcar todo.

C => Copiar los ítems marcados.

d => Poner una bandera de borrado.

D => Borra los ítems marcados.

x => Borra los ítems con bandera.

*m => Marca una región.

*u => Desmarca una región.

*% => Marca los archivos cuyo nombre coincide con una expresión regular.

*t => Intercambia la marca.

*c => Cambia el símbolo de la marca del viejo a uno nuevo.

g => Refresca el buffer Dired.

R => Renombra los ítems marcados.

O => Ejecuta chown en los ítems marcados.

G => Ejecuta chrgrp en los ítems marcados.

M => Ejecuta chmod en los ítems marcados.

D => Borra los ítems marcados.

F => Visita los ítems marcados. Este comando REQUIERE 'dired-x'.