# Curso de VSCode

Un pequeño repositorio donde aprenderemos un par de trucos para trabajar rápidamente con Visual Studio Code.

También hay un par de extensiones bastante útiles que les pueden servir.

## Comentar lineas

```
Shift+Cmd+7
Ctrl + } (revisar windows)
```

## Multi cursor y edición

### Clonar linea

```
Shift+Opt+ flecha abajo o arriba
```

### Multi cursor

```
Opt+Shift+ flecha abajo o arriba
```

### Multi cursor con ocurrencias

```
Mantener presionado Opt+doble click o seleccionar
```

### Seleccionar tab derecha izquierda

```
Shift+Opt+ flecha derecha o izquierda
```

## Ir a una línea especifica

```
⌘ P => luego escribir :
```

## Encontrar definiciones

Se puede buscar las diferentes definiciones: "variables, metodos, ..." 

```
Cmd + P => luego escribir la @
Se pueden agrupar si después de la @, se escriben :
```

## Snippets

* Abrir el buscador
```
Cmd+Shift+p luego escribir > Configure user snippets
```
* Seleccionar el lenguaje 
* Se abre el archivo en .json

```json
{
	// En la parte superior hay consejos

	"Show red console": {
		"prefix": "clgr",
		"body": "console.log('%c${1:Red Console}', 'color: white; background: red;')",
		"description": "Show a console.log with background red and white color"
	},
	"Clase": {
		"prefix": "cls",
		"body": [
			"export class ${1:NuevoSuperHeroe} {",
			"",
			"   constructor() {",
			"      $2",
			"   }",
			"}"
		],
	}
}
```
> Los archivos .md no reconocen los snippets 

* Insertar desde el buscador
```
Cmd+Shift+p > Insert snippet
```
* VS Code reconoce el tipo de archivo, buscar el snippet en la lista

## Tabs

### Cerrar tab

```
⌘ W      Cerrar tab  / Cerrar aplicación
⌘ K ⌘ W  Cerrar todas
⇧ ⌘ T    Reabrir anterior
⌃ TAB    Cambiar de tab
```


## Extensiones

* [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

* [Liveserver](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

* [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

* [TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
