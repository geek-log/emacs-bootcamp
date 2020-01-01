- [Emacs-Bootcamp](#emacs-bootcamp)
  * [Movement](#movement)
    + [Occur-Mode](#occur-mode)
- [Editing](#editing)
- [Special](#special)
  * [Term-Commands](#term-commands)
  * [EWW-Commands](#eww-commands)
  * [Dired-Commands](#dired-commands)
  * [Help](#help)
  * [Replace](#replace)
  * [Flyspell-Mode](#flyspell-mode)
- [Org-Mode](#org-mode)
  * [Basic](#basic)
  * [Tables](#tables)
  * [Links](#links)
  * [Subtrees](#subtrees)
  * [TODO-Lists](#todo-lists)
  * [Tags](#tags)
  * [Timestamps](#timestamps)
    + [Agenda-Timestamp](#agenda-timestamp)
    + [Point-On-Timestamp](#point-on-timestamp)
  * [Archiving](#archiving)
  * [Agenda-View](#agenda-view)
    + [Agenda-Dispatcher](#agenda-dispatcher)


- [Campo-Entrenamiento-Emacs](#campo-entrenamiento-emacs)
  * [Movimiento](#movimiento)
    + [Modo-Occur](#modo-occur)
- [Edición](#edición)
- [Especial](#especial)
  * [Comandos-Term](#comandos-term)
  * [Comandos-EWW](#comandos-eww)
  * [Comandos-Dired](#comandos-dired)
  * [Ayuda](#ayuda)
  * [Reemplazo](#reemplazo)
  * [Mode-Flyspell](#modo-flyspell)
- [Modo-Org](#modo-org)
  * [Básico](#básico)
  * [Tablas](#tablas)
  * [Enlaces](#enlaces)
  * [Subárboles](#Subárboles)
  * [Listas-TODO](#listas-todo)
  * [Etiquetas](#etiquetas)
  * [Marcas-De-Tiempo](#marcas-de-tiempo)
    + [Marca-De-Tiempo-Agenda](#marca-de-tiempo-agenda)
    + [Punto-En-Marca-De-Tiempo](#punto-en-marca-de-tiempo)
  * [Archivando](#archivando)
  * [Vista-De-Agenda](#vista-de-agenda)
    + [Despachador-de-Agenda](#despachador-de-agenda)


# Emacs-Bootcamp

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

C-x C-w => Saves the buffer as a new file. Prompts for the
                          new file name.

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

### Occur-Mode

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


## Special

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


### term-commands

C-c C-j => Enables term-line-mode.

C-c C-k => Enables term-char-mode.


### EWW-commands

M-<RET> => Opens the URL under the point on a new buffer.

b => Save bookmark.

B => List all bookmarks.

d => Download the URL under the point.

g => Reload the page.

S => List all open EWW buffers.

w => Copy the current URL to the kill ring.

M-C (Capital C and not Control) => Toggle colors.


### Dired-Commands

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


### Help

SPC => Scroll down the help menu.

DEL => Scroll up the help menu.

c => Show the command that a keybinding executes
                       (by typing a command name).

a => Apropos function, show information about a topic (i.e.: by
             typing a command name).

k => Show documentation that describes a command (by typing
               a command keybinding).

q => Quits the help menu.


### Replace

y => Change the current search match (say yes) and move to the next.

n => Don't change the current match (say no) and move to the next.

! => Change all matches found (say yes to all).

q => Quit the find-and-replace.


### Flyspell-Mode

C-M-i => Autocorrect the word before the point.

## Org-Mode

### Basic

      - TAB => Cycle through heading states: folded > child > subtree.

      - C-u C-u RET => Restarts to initial visibility.

      - C-u C-u C-u RET => Show all including drawers.

      - M-RET => Insert a new heading, item or row.

      - C-RET => Insert a new heading at the end.

      - M-UP / M-DOWN => Switch the current item with the previous/next one.

      - M-LEFT => Promotes the current heading one level up.

      - M-RIGHT => Demotes the current heading one level down.

      - C-c ^ => Order same level entries.

      - C-c * => Turn normal line into a heading.

      - Add TODO to a heading => Turn heading into a TODO item.

      - M-S RET => Add a new TODO entry below the current one.

      - C-c / => Build sparse tree.

      - M-g n => Jump to next sparse tree.

      - M-g p => Jump to previous sparse tree.

      - C-c C-c => Remove highlights.

      - M-RET => Insert a new heading, item or row.

      - C-S-RET => Insert a new checklist item.

      - S-UP/S-DOWN => Jump to previous/next item on the list.

      - S-LEFT, S-RIGHT => Change the type of list.

      - M-LEFT, M-RIGHT => Increment or decrement the level of identation.

      - C-c C-x d => Inserts a new drawer.

      - <c TAB => Insert a center text block.

      - <e TAB => Insert an example block.

      - <l TAB => Insert a latex block.

      - <s TAB => Insert a code block.

      - <q TAB => Insert a quote block.

      - <v TAB => Insert a verse block.

      - C-c C-c => Execute code on source code block.

      - C-c c => Capture command.

      - C-c C-e => Call the Export Dispatcher.

### Tables

       - C-c C-c => Aligns a table.

       - TAB, RET => Aligns a table and moves to the next field.

       - S-TAB => Aligns a table and moves to the previous field.

       - C-c | => Transforms a selected region into a table.

       - C-c - => Inserts a new horizontal rule under the current line.

       - C-c <SPC> => Clear the field under the point.

       - M-a => Move the point to the beggining of the current field.

       - M-e => Move the point to the end of the current field.

       - M-LEFT, M-RIGHT => Move the current column to the left/right.

       - M-UP, M-DOWN => Move the current row up/down.

       - M-S-LEFT => Kill the current column.

       - M-S-RIGHT => Insert new column to the right.

       - M-S-UP => Kill the current row.

       - M-S-DOWN => Insert a new row above the current row.

       - C-c ^ => Order the table rows.

       - C-c + => Sums all the items on the current column or in the
         rectangle defined by the current region.

       - S-RET => If the current field is empty copy it from the first non empty
         field.

       - C-c ` => Edits the current field on another buffer. Useful for long
         fields that are not fully visible.

       - M-x org-table-export => Exports a table to a file.

       - M-x org-table-import => Imports a file as a table.

       - C-c = => Installs a formula on the current table cell.

       - C-c * => Recomputes the current row.

       - C-u C-c * => Recomputes the whole table.

       - M-x orgtbl-ascii-plot => Plots a table using text histograms.

       - M-x org-plot/gnuplot => Plots a table using Gnuplot, needs Gnuplot
         to be installed.


### Links

     - C-c l => Store link that can later be pasted using C-c C-l.

     - C-c C-l => If the point is on an empty line, paste a stored link. If
       the point is over a link, edits the link.

     - C-c C-o => If the point is on a link, save the current position
       on the mark ring and JUMP to the link.

     - C-c & => Jump back to the saved mark.

     - C-c % => Add current position to the mark ring.

     - C-u C-c C-l => Insert a link to a file.

     - C-c C-x C-n => Jump to next link on the buffer.

     - C-c C-x C-p => Jump to previous link on the buffer.

### Subtrees

     - TAB => Cycle between the states 'folded' > 'child' > 'subtree' on
       the current heading (current subtree).

     - S-TAB => Cycle between the states 'folded' > 'child' > 'subtree' on
       the whole tree (all the org document).

     - C-u C-u TAB => Restarts to the startup visibility.

     - C-u C-u C-u TAB => Show all including drawers.

     - C-c C-r => Reveal command, reveals the context around the point.

     - C-c C-k => Exposes all tree headings.

     - C-c TAB => Expose all subtree direct children.

     - C-c C-x b => Show the subtree in an indirect buffer.

     - C-c C-x v => Copy the visible subtree text.

     - C-c C-n => Next visible heading.

     - C-c C-p => Previous visible heading.

     - C-c C-f => Next heading on the same level.

     - C-c C-u => One heading level up.

### TODO-Lists

     - C-c C-t => Rotate the TODO state: 'unmarked', 'TODO', 'DONE'.

     - S-RIGHT / S-LEFT => Change the TODO item state.

     - C-c / t => Display all TODO items in a sparsed tree, folds all the
       buffer and show all 'TODOs' not marked as 'DONE'.

     - C-c / T => Search for a specific TODO item.

     - S-M-RET => Inserts a new TODO below the current one.

     - C-c , => Set priority.

     - S-UP / S-DOWN => Increase/Decrease priority.

     - C-c C-x C-b => Toggle checkbox status.

     - M-S-RET => Insert a new checkbox item.

     - C-c C-x o => Toggle 'ORDERED' property, this is used if the
       checkboxes needs to be turned on using a particular sequence.

     - C-c # => Updates the 'statistic cookie'.

### Tags

     - C-c C-c => Add tags to a heading.

     - C-c \ => Builds a sparse tree with all headings that matches with
       a tags search.

     - C-c C-x p => Insert a property.

     - C-u M-x => Insert property on the current drawer.

     - C-c C-c d => Deletes a property.

     - C-c C-c D => Deletes a property globally.

     - S-RIGHT, S-LEFT => Change the property by cycling on the allowed
       values.

     - C-c C-c => When the point is over a property, execute the property
       commands.

     - C-c C-c c => Compute a property at the point.

     - C-c \ => Build a sparsed tree with all matching entries.

     - C-c / p  => Build a sparsed tree based on a property value.

### Timestamps

     - C-c . => Prompts for a date and inserts a timestamp.

     - C-c ! => Inserts a inactive timestamp.

     - C-c < => Inserts today's date.

     - C-c C-o => Access the agenda for the given timestamp.

     - C-c C-d => Insert 'DEADLINE'. This will be listed on the agenda.

     - C-c C-s => Insert 'SCHEDULED'.

     - C-c / d => Build a sparsed tree with all deadlines.

     - C-c / b => Build a sparsed tree with all deadlines previous to
       a given date.

     - C-c C-x C-i => Starts the clock for the current item.

     - C-c C-x C-o => Inserts another timestamp on the same location where
       the clock was started before (stops the clock).

     - C-c C-x C-x => Reclock the last clocked time.

     - C-c C-x C-e => Updates the effort estimate.

     - C-c C-y => Recomputes the time.

     - C-c C-t => Changes a TODO task to DONE and stops the clock.

     - C-c C-x C-q => Cancels the current clock.

     - C-c C-x C-j => Jump to the currently clocked heading.

     - C-c C-x C-d => Displays the time of each subtree.

#### Agenda-Timestamp

     - q => Quits the Agenda timestamp view.

     - S-UP, S-DOWN, S-RIGHT, S-LEFT => Move on the calendar.

     - M-S-RIGHT, M-S-LEFT => Move to the next/previous month.

     - M-S-UP, M-S-DOWN => Move to the next/previous year.

     - <, > => Scroll a month on the calendar.

#### Point-On-Timestamp

     - S-UP, S-DOWN => Increases or decreases the year, month, day, hour or
       minute depending on the portion of the timestamp where the point is
       located.

### Archiving

     - C-c C-x C-a => Archive the current entry.

     - C-c $ => Archive the current subtree.

### Agenda-View

     - C-c a => Agenda View Command.

#### Agenda-Dispatcher

     - a => Create an agenda.

     - t => Create a TODO list.

     - T => Create a list of headings matching a regular expression.

     - s => Search.

     - / => Multi-occur.

     - q => Quit the Agenda Dispatcher.

     - n => Move to next agenda entry.

     - p => Move to previous agenda entry.




# Campo-Entrenamiento-Emacs

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

C-x C-w => Guarda el buffer como un nuevo archivo. Pregunta por
           el nombre para el nuevo archivo.

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

### Modo-Occur

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


### Ayuda

SPC => Hacer scroll hacia abajo en el menú de ayuda.

DEL => Hacer scroll hacia arriba en el menú de ayuda.

c => Muestra el comando que un teclazo ejecuta (digitando
     el nombre de un comando).

a => Función apropos, muestra información sobre un tópico (ej: al
      digitar el nombre de un comando).

k => Muestra documentación que describe un comando (al digitar
     un teclazo).

q => Quita el menú de ayuda.


### Reemplazo

y => Cambie la coincidencia de búsqueda actual (decir sí) y moverse a la
     próxima.

n => No cambie la coincidencia actual (diga no) y muévase a la siguiente.

! => Cambie todas las coincidencias que encuentre (decir sí a todo).

q => Quitar la búsqueda y reemplazo.


### Modo-Flyspell

C-M-i => Auto-corregir la palabra antes del punto.


## Especial

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


### Comandos-Term

C-c C-j => Habilita el modo term-line-mode.

C-c C-k => Habilitar el modo term-char-mode.


### Comandos-EWW

M-<RET> => Abre el URL bajo el punto en un nuevo buffer.

b => Guarde el marcador (bookmark).

B => Listar todos los marcadores.

d => Descargar el URL bajo el punto.

g => Recargar la página.

S => Listar todos los buffers EWW abiertos.

w => Copiar el URL actual al anillo kill.

M-C (Capital C and not Control) => Habilitar/Deshabilitar los colores.


### Modo-Dired

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


## Modo-Org

### Básico

      - TAB => Ciclar a través de los estados de encabezado: 'doblado' >
        'hijo' > 'subárbol'.

      - C-u C-u RET => Reiniciar a la visibilidad inicial.

      - C-u C-u C-u RET => Mostrar todo incluidos los cajones.

      - M-RET => Insertar un nuevo encabezado, ítem o fila.

      - C-RET => Insertar un nuevo encabezado al final.

      - M-UP / M-DOWN => Intercambiar el ítem actual con el próximo/previo.

      - M-LEFT => Promueve el encabezado actual un nivel.

      - M-RIGHT => Degrada el encabezado un nivel.

      - C-c ^ => Ordena entradas en el mismo nivel.

      - C-c * => Convierte una línea normal en un encabezado.

      - Add TODO to a heading => Convierte un encabezado en un ítem TODO.

      - M-S RET => Agrega un nuevo ítem TODO bajo el actual.

      - C-c / => Construir un árbol esparcido.

      - M-g n => Saltar al próximo árbol esparcido.

      - M-g p => Saltar al árbol esparcido previo.

      - C-c C-c => Remover el resaltado.

      - M-RET => Insertar un nuevo encabezado, ítem o fila.

      - C-S-RET => Insertar un nuevo ítem de checklist.

      - S-UP/S-DOWN => Saltar al previo/próximo ítem de la lista.

      - S-LEFT, S-RIGHT => Cambiar el tipo de lista.

      - M-LEFT, M-RIGHT => Incrementar o decrementar el nivel de indentación.

      - C-c C-x d => Insertar un nuevo cajón.

      - <c TAB => Insertar un bloque de centrado.

      - <e TAB => Insertar un bloque de ejemplo.

      - <l TAB => Insertar un bloque de latex.

      - <s TAB => Insertar un bloque de código.

      - <q TAB => Insertar un bloque de cita.

      - <v TAB => Insertar un bloque de verso.

      - C-c C-c => Ejecutar código en un bloque de código.

      - C-c c => Comando de Captura.

      - C-c C-e => Llamar al despachador de exportación.

### Tablas

       - C-c C-c => Alinear una tabla.

       - TAB, RET => Alinea una tabla y se mueve al próximo campo.

       - S-TAB => Alinea una tabla y se mueve el campo previo.

       - C-c | => Transforma la región seleccionada en una tabla.

       - C-c - => Inserta una nueva regla horizontal bajo el punto.

       - C-c <SPC> => Limpiar el campo bajo el punto.

       - M-a => Mover el punto al principio del campo actual.

       - M-e => Mover el punto al final del campo actual.

       - M-LEFT, M-RIGHT => Mover la columna actual a la izquierda/derecha.

       - M-UP, M-DOWN => Mover la fila actual hacia arriba/abajo.

       - M-S-LEFT => Matar la columna actual.

       - M-S-RIGHT => Insertar una nueva columna a la derecha.

       - M-S-UP => Matar la fila actual.

       - M-S-DOWN => Insertar una nueva fila sobre la actual.

       - C-c ^ => Ordenar las filas de la tabla.

       - C-c + => Sumar todos los ítems en la columna actual o en el
         rectángulo definido por la región actual.

       - S-RET => Si el campo actual está vacío, cópielo del primer campo
         no vacío.

       - C-c ` => Edita el campo actual en otro buffer. Útil para campos
         muy largos que no son completamente visibles.

       - M-x org-table-export => Exporta una tabla a un archivo.

       - M-x org-table-import => Importa un archivo como una tabla.

       - C-c = => Instala una fórmula en la celda actual de la tabla.

       - C-c * => Recomputar la fila actual.

       - C-u C-c * => Recomputar la tabla completa.

       - M-x orgtbl-ascii-plot => Graficar una tabla usando histogramas.

       - M-x org-plot/gnuplot => Graficar una tabla usando Gnuplot, necesita
         Gnuplot.

### Enlaces

     - C-c l => Almacenar un enlace que luego puede pegarse usando C-c C-l.

     - C-c C-l => Si el punto está en un línea vacía, pega un enlace
       almacenado. Si el punto está sobre un enlace, edita el enlace.

     - C-c C-o => Si el punto está en un enlace, guarda la posición actual
       en el anillo de marcas y SALTA al enlace.

     - C-c & => Saltar a la marca guardada.

     - C-c % => Agrega la posición actual al anillo de marcas.

     - C-u C-c C-l => Inserta un enlace a un archivo.

     - C-c C-x C-n => Salta al próximo enlace en el buffer.

     - C-c C-x C-p => Salta al enlace previo en el buffer.

### Subárboles

     - TAB => Ciclar entre los estados 'doblado' > 'hijos' > 'subárbol'
       del encabezado actual.

     - S-TAB => Ciclar entre los estados 'doblado' > 'hijos' > 'subárbol'
       en todo el árbol (el documento completo).

     - C-u C-u TAB => Reinicia a la visibilidad inicial.

     - C-u C-u C-u TAB => Mostrar todo incluidos los cajones.

     - C-c C-r => Comando de revelar, revela el contexto alrededor del punto.

     - C-c C-k => Expone todos los encabezados de un subárbol.

     - C-c TAB => Expone todos los hijos directos de un encabezado.

     - C-c C-x b => Muestra el subárbol en un buffer indirecto.

     - C-c C-x v => Copiar el texto visible del subárbol.

     - C-c C-n => Próximo encabezado visible.

     - C-c C-p => Encabezado visible previo.

     - C-c C-f => Próximo encabezado en el mismo nivel.

     - C-c C-u => Un encabezado arriba.

### Listas-TODO

     - C-c C-t => Rotar los estados TODO: 'desmarcado', 'TODO', 'DONE'.

     - S-RIGHT / S-LEFT => Cambiar el estado del ítem TODO.

     - C-c / t => Desplegar todos los ítems TODO en un árbol esparcido y
       despliega todos los 'TODOs' no marcados como 'DONE'.

     - C-c / T => Busca por un ítem TODO específico.

     - S-M-RET => Inserta un nuevo TODO bajo el actual.

     - C-c , => Establece la prioridad·

     - S-UP / S-DOWN => Incrementa/Decrementa la prioridad.

     - C-c C-x C-b => Habilita o deshabilita un checkbox.

     - M-S-RET => Inserta un nuevo ítem de checkbox.

     - C-c C-x o => Habilita la propiedad 'ORDERED' que es usada cuando
       los checkboxes necesitan encenderse en una secuencia particular.

     - C-c # => Actualiza la 'galleta estadística'.

### Etiquetas

     - C-c C-c => Agrega etiquetas a un encabezado.

     - C-c \ => Construye un árbol esparcido con todos los encabezados que
       concuerdan con un búsqueda de etiquetas.

     - C-c C-x p => Inserta una propiedad.

     - C-u M-x => Inserta una propiedad en el cajón actual.

     - C-c C-c d => Borra una propiedad.

     - C-c C-c D => Borra una propiedad globalmente.

     - S-RIGHT, S-LEFT => Cambiar la propiedad ciclando en los valores
       permitidos.

     - C-c C-c => Cuando el punto está encima de una propiedad, ejecute
       los comandos de la propiedad.

     - C-c C-c c => Computa una propiedad en el punto.

     - C-c \ => Construir un árbol esparcido con todas las entradas que
       concuerden.

     - C-c / p  => Construir un árbol esparcido basado en el valor de una
       propiedad.

### Marcas-de-Tiempo

     - C-c . => Pregunta por una fecha e inserta una marca de tiempo.

     - C-c ! => Inserta una marca de tiempo inactiva.

     - C-c < => Inserta la fecha de hoy.

     - C-c C-o => Accesa la agenda para la marca de tiempo dada.

     - C-c C-d => Inserta un 'DEADLINE'. Esto se listará en la agenda.

     - C-c C-s => Inserta un 'SCHEDULED'.

     - C-c / d => Construye un árbol esparcido con todos los deadlines.

     - C-c / b => Construye un árbol esparcido con todos los deadlines
       previos a una fecha dada.

     - C-c C-x C-i => Inicia el reloj para el ítem actual.

     - C-c C-x C-o => Inserta otra marca de tiempo en la misma ubicación
       adonde el reloj fue iniciado antes).

     - C-c C-x C-x => Volver a tomar el último tiempo tomado.

     - C-c C-x C-e => Actualiza el estimado de esfuerzo.

     - C-c C-y => Recomputa el tiempo.

     - C-c C-t => Cambia una tarea TODO a DONE y detiene el reloj.

     - C-c C-x C-q => Cancela el reloj actual.

     - C-c C-x C-j => Salta al encabezado al que se le está tomando el
       tiempo actualmente.

     - C-c C-x C-d => Despliega el tiempo en cada subárbol.

#### Marca-De-Tiempo-Agenda

     - q => Quita la vista de Agenda.

     - S-UP, S-DOWN, S-RIGHT, S-LEFT => Moverse en el calendario.

     - M-S-RIGHT, M-S-LEFT => Moverse al próximo/previo mes.

     - M-S-UP, M-S-DOWN => Moverse al próximo/previo año.

     - <, > => Hacer scroll de un mes en el calendario.

#### Punto-En-Marca-De-Tiempo

     - S-UP, S-DOWN => Incrementa o decremente el año, mes día, hora o
       minuto dependiendo de la porción de la marca de tiempo en donde el
       punto esté ubicado.

### Archivando

     - C-c C-x C-a => Archiva la entrada actual.

     - C-c $ => Archiva el subárbol actual.

### Vista-De-Agenda

     - C-c a => Comando de Vista de Agenda.

#### Despachador-Agenda

     - a => Crea una agenda.

     - t => Crea una lista TODO.

     - T => Crear una lista de encabezados que concuerdan con una expresión
       regular.

     - s => Buscar.

     - / => Multi-occur.

     - q => Quitar el despachador de Agenda.

     - n => Moverse a la próxima entrada de la agenda.

     - p => Moverse a la entrada previa de la agenda.