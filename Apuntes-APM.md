# Periodismo de datos

Funciones de un ordenador. Tomar notas, navegador y línea de comandos. El periodismo de datos se puede hacer con consola, Excel.... lo importante es pensar en términos de datos.

Editores similares: (https://blog.infotics.es/2015/11/11/editor-de-textos/) Atom, Sublime, Notepad++, Haroopad (es complementario porque funciona con Markdown que es una sintaxis simple).
- EMACS. Editor de texto y casi puede ser un sistema operativo. Curva de aprendizaje muy alta. Trabaja con tablas. Si solo trabajas con ello puedes llamar a una tabla a través de otra (lo que hice con la wiki lo puedo hacer con EMAX)
- VIM. Lenguaje de datos también muy potente.

*Markdown. Sintaxis simple – información estructurada.*
Buscadores alternativos: DuckDuckGo; Qwant; StartPage; SearX

**Operadores booleanos de búsqueda:**
- 'Site' = site:leganesactivo.com; site:diezminutos.com
- 

**Guardar las bases de datos .csv – compatible con todo y poco espacio.**

- **Git** es un sistema de gestión de versiones. Hay que descargarlo como complemento de Cypwin (en el mismo archivo .exe de Cypwin darle a 'full' y elegir 'git' y 'nano'). Nace en el mundo linux para la gestión del desarrollo de Linux en el que participan miles de programadores de todo el mundo de forma cooperativa por fases.
-- Para los periodistas: Puede que sea útil para llegar a una versión anterior del trabajo que has hecho. Se usa por mucha gente y la comunidad se llama GitHub: repositorio de lo que se hace en periodismo de datos. Esos proyectos se pueden descargar en tu ordenador o clonar en tu GitHub. Si después de clonarlo quieres editar ese documento lo puedes hacer y avisar al autor para que lo mejore, el puede aceptar o no. Es un portal colaborativo, es decir, app en línea.
- **StackOverFlow**: Preguntas y respuestas sobre programación.

- Cygwin. Emulación de Linux en Windows. Consola de comandos.
-- **Comandos**: listas de comandos posibles en varias webs.
-- pwd: Print Working Directory: ruta relativa sobre cypwig no ruta absoluta de windows.
-- find : encontrar archivos.
-- cd : cambiar de directorio.
-- $ : Pront, es decir, petición de orden. Es configurable.
-- ls: listar archivos de este directorio.
-- ls -la: listar todos los directorios a los que se puede tener acceso.
-- Ctrl+C : parar proceso.
-- Doble tabulador: autocompletar. **No debe haber espacios**
-- - - help: te dice qué hace ese comando.
-- man: te muestra ese comando tal y como sale en manuales.
-- more y less: visores documentos de texto.
-- Ctrl+L: Clear.
-- CD: Volver al directorio principal.
-- Ctrl+R: Búsqueda entre las órdenes que has dado recientemente.
-- Cat: Concatenar archivos, es decir, unir en uno varios archivos. También lee lo que hay dentro de un archivo en caso de que sea texto plano, con un odt, pdf no funciona.
-- Nano: Editor de texto en cypwig.
-- Echo: Devuelve lo que has escrito.
-- >: Envía lo que se debería reflejar en la cosola a otro archivo. Si este archivo existiera, sustituiría el contenido anterior.
-- >>: Añade lo que se debería reflejar e la consola al archivo existente respetando el contenido que tenga el archivo.
-- Touch: Crear archivo vacío. Puedes crear varios a la vez.
-- Rm: Borrar.
-- Rm -R: Borrar de forma recursiva.
-- Rm -F: Forzar borrado.
-- lynx: Navegador en línea de comados.
-- Source: Código fuente de la página.
-- . : Afecta al directorio donde estás.
-- File: Dice qué tipo de archivo es (detector de virus, p.ej)
-- Mkdir: Crear una carpeta, hay que indicar el nombre del archivo y estar donde queremos alojarlo.
-- Mv: Mover un archivo a otro archivo es renombrar. ('mv borrar limpiar' y el archivo borrar pasa a llamarse limpiar). El destino puede ser único pero el origen pueden ser varios.
Mover todos los txt : (asterisco).txt
Alguna de sus opciones son:
-f forzoso, sobrescribe archivos destino si existen.
-i avisa antes de sobrescribir archivos existentes.
-v verboso, escribe el nombre de cada archivo que mueve.
-u no mover si existe archivo destino más nuevo o de igual fecha.
-- Rm -rf txt/(asterisco) = borrar todo el contenido de una carpeta.
-- Rm -rf txt = borrar la carpeta y el contenido.
-- Cp: Copiamos archivos y/o directorios.
-- Cp -r: Copiamos una carpeta y su contenido, sino no.
-- Cp -A: Copiamos con los mismos permisos.
-- Env: Variables de entorno de Bash.
-- | : Manda la salida de un comando a otro. Hace las funciones de '>' pero en otro programa (more o less: paginador)
** -- Cuando escribimos una '/' estamos diciendo que es una carpeta **

- BASH (la consola) tiene una API (Interfaz de la aplicación de programa) estas tienen 3 órdenes solo.
-- Stdout: Salida estandard
-- Stdin: Entrada estandard
-- Stderr: Salida de errores: 'no se encontró la orden', por ejemplo.

#Apt-cyg
Instalador de paquetes o programas. El atributo es 'install'
*apt-cyg install*

-- imagemagick : manipular imágenes.

-- Emacs : para editor de texto. Se puede tener dentro de la consola.

-- Python : para trabajar con Python (el que más se usa y más ha crecido)

-- R : para trabajar con R (análisis estadístico)

-- Perl : para trabajar con Perl (trabaja con texto y expresiones regulares) Muy valorado.

Ejemplo: 'lo que está entre esta palabra y esta palabra envíalo a este archivo'; fue el proceso de trabajo para España en llamas con el BOE, cogió el nombre del sitio y la extensión para hacer un mapa.
axios.com -- web especializada con visualización de datos.
-- Ruby : para trabajar con Ruby (lenguaje de escritura fácil)
-- Tesseract : herramienta de reconocimiento óptico de caracteres.
-- pdfgrep : analizar el PDF y realizar búsquedas en el texto.
-- grep : realizar búsquedas de texto.
-- sgrep : realizar búsquedas en un texto de SGML XML o HTML.
-- awk : procesar texto (enviar información concreta 'las primeras palabras de cada línea' p.ej, editarla...) y lenguaje de programación. http://www.francisconi.org/linux/comandos/awk
-- gawk : procesar texto también.
-- sed : editar flujos de texto (buscar y reemplazar palabras, caracteres...)
-- xlsx2csv : pasar de xlsx a csv.
-- p7zip : archivar y comprimir datos.
-- gzip : compresor de datos.
-- qpdf : transformación de PDF.
-- xpdf : visionar y otras operaciones PDF.

## Beneficios de la consola
Ahorras tiempo, te ofrecen alternativa a GUI (entorno), te acerca a los sistemas POSIX, funcionas con atajos compartidos, te preparan para la programación, aprendes otra forma de hacer las cosas, te empondera.

## Atajos de la consola y el ordenador
-- Alt+Tab : Cambiar de programa.
-- Ctrl+L : Escribir en la barra de navegador. Limpiar la consola de Bash.
-- Ctrl+U : Código fuente de una web en el navegador.
-- Ctrl+T : Nueva pestaña en el navegador.
-- Ctrl+A : Principio de línea.
-- Ctrl+E : Final de línea.
-- Ctrl+C : Parar el proceso.
-- Ctrl+Shift+V : Pegar.
-- Ctrl+Shift+C : Copia.
-- Ctrl+A : Seleccionar todo.

## Jugar con datos
-- Wc : Contar palabras, caracteres o bites que tiene un archivo.
-- Wc -c: Bytes.
-- Wc -m: Caracteres.
-- Wc -l: Líneas.
-- Wc -L: Máximo de longitud del display (pantalla)
-- Wc -w: Palabras.
-- Curl -L : Descargar un archivo desde una URL aunque tenga redirección.
-- Diff : Compara dos archivos.
-- Head: Muestra las diez primeras líneas.
-- Tail: Muestra las diez últimas líneas.
-- ../ : Ruta relativa que sube un escalón jerárquico.
-- Du -sh: Muestra lo que pesa un archivo.
-- Cut: Escoge lo que quieres extraer de un archivo.
-f: indica las filas que quieres elegir (con número).
-d: indicas donde tiene que parar de extraer.
-- Split : Dividir un archivo.
-- Grep -rn : Busca de forma recursiva y numera las líneas.
-- Grep -rn | Wc -l : Cuenta los resultados.
-- Grep -c : Cuenta los resultados.
-- Grep -rn | Grep -rn: Busca sobre el resultado de la primera búsqueda. Solo hay que poner el archivo al que afecta en el primer comando.
-- Grep [0-9] : Mostrar líneas que contengan números.
-- Grep [A-Z] : Mostrar líneas en las que haya letras.
-- Wc -i : No hace distinción entre mayúsculas y minúsculas.

## OpenRefine
Web para analizar tablas de datos mucho más ágil. Puede quedarse pillado con docuemntos muy grandes.
1 Subir archivo
2 Cambiar el nombre de código si algunos caracteres no los reconoce.
3 Crear proyecto.
4 Facet/Filter : Filtros del documento.

## Github
Gestor de versiones. Página web en la que se pueden subir varias versiones de un mismo documento para poder controlar lo que hemos hecho y tener un punto de retorno a la hora de trabajar.
-- Repositorio: Proyecto.
-- Gist: Archivo.
-- Organización.

Git es un ¿idioma? y Github un gestor. El idioma sirve también para otros servidores como Gitlab o Bitbucket o en un servidor externo. 