# sublime-settings
Sublime text 3 settings files


## Набор настроек Sublime text 3 для работы с питонячими файлами.

1. Установить Package Control;
2. Установить пакет Anaconda;
3. Установить пакет SublimeREPL и настроить его в соответствии с [Этим руководством](https://gist.github.com/simplesasha/73005e8e08065d8c360dba09dc86626b);
4. Создать New build:

```json
	{
		"target": "run_existing_window_command",
		"id": "repl_python_run",
		"file": "config/Python/Main.sublime-menu"
	}
```
5. Настройки Anaconda:
```json
	{
		"auto_formatting": true,
		"autoformat_ignore":
		[
			"E501"
		],
		"pep8_ignore":
		[
			"E501"
		],
		"anaconda_linter_phantoms": false,
		"anaconda_gutter_marks": true,
		"anaconda_gutter_theme": "simple",
		"anaconda_linter_mark_style": "none",
		"disable_anaconda_completion": false,
	}
```
6. Настройки Sublime text:
```json
	{
		"color_scheme": "Packages/Color Scheme - Default/Monokai.sublime-color-scheme",
		"font_size": 12,
		"ignored_packages":
		[
			"Vintage"
		],
		"theme": "Adaptive.sublime-theme"
	}
```
7. Установить пакет __BracketGuard__;
