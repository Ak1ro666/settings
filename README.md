<h1 align="center">Привет я <a href="#!" target="_blank">Антон</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Я студент, а также фронтенд разработчик</h3>
<h2 align="center">Здесь собраны основные мои настройки</h3>


# Мои шрифт: 
      FiraCode,
      JetBrains.

# Нужные приложения в работе: 
      Focus To-Do(Таймер помодоро),
      Figma(Макеты),
      Insomnia(Отправка запросов для проверки),
      PowerToys(много полезный функций, в том числе пиккер).

# Расширения для браузера:
      Vimbox переводчик - лучший переводчик,
      JSON Formatter - для онглайн форматирования формата json,
      React Developers Tools - Для проверки React кода в браузере,
      Redux Dev Tools - Аналогично React Developers Tools, но с Redux,
      WhatFont - Узнать какой шрифт при наведении мышкой на слово.
      TypeScript Editor - позволяет писать TypeScript прямо в браузере.

# Мои любимые темы и иконки:
      Bearded Theme Vivid Black,
      Tol,
      soft sight,
      mokka,
      Hacker Theme,
      Andromeda,
      Icons.

# Лучшие расширения для VsCode: 
      Auto Close Tag - Автоматическое закрытия тегов,
      Auto Complete Tag - Автоматическое заверешени тегов,
      Auto Rename Tag - Автоматическое переименование тегов,
      Backticks - Автосмена ковычек при вставки переменной в обычные ковычки '${}',
      Bootstrap IntelliSense - Подсказки bootstrap,
      Code Spell Cheker - Автоматическая проверка на грамматические ошибки,
      eCsstractor for VSCode - Автоматическое копирование всех css тегов,
      Simple React Snippets - Подсказки для реакт,
      filesize - Размер файла,
      HTML CSS Support - Дополнительная поддержка html, css,
      htmltagwrap - команда для оборачивания выделенного кода в тег,
      Image preview - Просмотр картинки при нажатии на неё,
      Import Cost - Показывает сколько весит подключённая библиотека,
      Live Server - Запуск локального сервера,
      Path intellisense - Делает лучше способы путей к файлам,
      Prettier - Автоматическое форматирование кода,
      Project Manager - Показывает твои сохранённые проекты, быстрая навигация,
      Sass (.sass only) - Поддержка sass,
      Live Sass Compiller - Автоматическая компиляция кода из scss в css,
      Svg Preview - Показывает картинки вставленные в коде,
      Tabnine - AI, которое подсказывает части кода.

# Мои настройки settings.json
            {
	      // Editor Settings
	      "editor.snippetSuggestions": "top",
      	"editor.tabSize": 2,
	      "editor.codeActionsOnSave": {
	      	"source.organizeImports": "explicit"
	      },
	      "editor.formatOnSave": true,
	      "editor.wordWrap": "bounded",
	      "workbench.colorTheme": "Bearded Theme HC Minuit",
	      "editor.wrappingIndent": "same",
	      "editor.wordWrapColumn": 80,
	      "editor.detectIndentation": true,
	      "editor.insertSpaces": false,
	      "workbench.editor.tabSizing": "shrink",
	      "workbench.startupEditor": "newUntitledFile",
	      "editor.folding": false,
	      "editor.bracketPairColorization.enabled": false,
	      "editor.smoothScrolling": true,
	      "editor.glyphMargin": false,
	      "window.density.editorTabHeight": "compact",
	      "workbench.activityBar.location": "top",
	      "editor.accessibilitySupport": "off",
	      "window.commandCenter": false,
	      "workbench.layoutControl.enabled": false,
	      "editor.fontSize": 16,
	      "editor.lineHeight": 26,
	      "editor.unicodeHighlight.ambiguousCharacters": false,
	      "editor.quickSuggestionsDelay": 0,
      	"html.completion.attributeDefaultValue": "singlequotes",
	      "editor.linkedEditing": true,
	      "html.autoClosingTags": true,
      	"javascript.autoClosingTags": true,
      	"typescript.autoClosingTags": true,
	      "editor.suggestSelection": "first",
	      "editor.fontLigatures": true,
	      "editor.scrollbar.horizontal": "hidden",
	      "editor.scrollbar.vertical": "hidden",
	      "editor.renderControlCharacters": false,
	      "editor.cursorBlinking": "expand",
	      "editor.cursorStyle": "line-thin",
	      "editor.cursorWidth": 2,
	      "editor.cursorSmoothCaretAnimation": "explicit",
      	"editor.tokenColorCustomizations": {
	      	"textMateRules": [
		      	{
			      	"scope": [
				      	"comment",
					      "entity.name.type.class",
					      "keyword",
					      "constant",
					      "storage.modifier",
				      	"storage.type.class.js"
				      ],
				      "settings": {
				      	"fontStyle": "italic"
			      	}
			      },
		      	{
				      "scope": [
					      "invalid",
					      "keyword.operator",
				      	"constant.numeric.css",
				      	"keyword.other.unit.px.css",
					      "constant.numeric.decimal.js",
				      	"constant.numeric.json"
				      ],
			      	"settings": {
			      		"fontStyle": ""
			      	}
			      }
		      ]
      	},

	      "editor.defaultFormatter": "esbenp.prettier-vscode",
	      "editor.fontFamily": "Iosevka, Maple Mono, JetBrains Mono, Cascadia Code PL, IBM iScript REDGroup",
	      "editor.renderWhitespace": "none",
      	"editor.stickyScroll.enabled": true,
      	"editor.showFoldingControls": "always",

	      // Prettier Settings
	      "prettier.tabWidth": 2,
      	"prettier.useTabs": true,
      	"prettier.singleQuote": true,
	      "prettier.jsxSingleQuote": true,
      	"prettier.trailingComma": "all",
	      "prettier.semi": true,
	      "prettier.bracketSameLine": true,
	      "prettier.arrowParens": "avoid",
	      "prettier.printWidth": 100,

	      // Project Manager
      
	      "projectManager.git.baseFolders": ["$home/workspace"],
	      "projectManager.sortList": "Recent",

      	// Emmet Settings
	      "emmet.includeLanguages": {
	      	"javascript": "javascriptreact",
	      	"html": "html"
	      },
	      "emmet.triggerExpansionOnTab": true,

	      // Explorer Settings
	      "explorer.compactFolders": false,
	      "explorer.enableDragAndDrop": true,
	      "explorer.confirmDragAndDrop": false,

      	// Debug Settings
      	"debug.toolBarLocation": "hidden",
	      "debug.focusWindowOnBreak": false,
      	"debug.showInlineBreakpointCandidates": false,
	      "debug.showBreakpointsInOverviewRuler": false,

	      // Terminal Settings
	      "terminal.integrated.profiles.windows": {
	      	"GitBash": {
	      		"path": "D:/Git/bin/bash.exe"
	      	}
	      },
	      "terminal.integrated.defaultProfile.windows": "Git Bash",

	      // Language-Specific Settings
	      "[javascript]": {
	      	"editor.defaultFormatter": "esbenp.prettier-vscode"
	      },
      	"[css]": {
	      	"editor.defaultFormatter": "esbenp.prettier-vscode"
	      },
	      "[html]": {
	      	"editor.defaultFormatter": "esbenp.prettier-vscode"
	      },
      	"[scss]": {
	      	"editor.defaultFormatter": "esbenp.prettier-vscode"
	      },
      	"[jsonc]": {
	      	"editor.defaultFormatter": "esbenp.prettier-vscode"
      	},

	      // Other Settings
	      "files.autoSave": "afterDelay",
      	"json.schemas": [
	      	{
      			"fileMatch": ["/myfile"],
	      		"url": "schemaURL"
	      	}
      	],
	      "security.workspace.trust.untrustedFiles": "open",
	      "javascript.updateImportsOnFileMove.enabled": "always",

      	// CSpell Settings
      	"cSpell.userWords": ["Показать", "Скрыть", "список"],

	      // Live Server Settings
	      "liveServer.settings.donotVerifyTags": true,

	      // Update Settings
	      "update.mode": "manual",

	      // Workbench Settings
      	"workbench.sideBar.location": "right",
      	"workbench.iconTheme": "catppuccin-perfect-sequoia",
      	"workbench.colorCustomizations": {},
      	"workbench.productIconTheme": "el-vsc-v1-icons",

	      // File Associations
      	"files.associations": {
	      	"*.scss": "tailwindcss",
	      	"*.module.scss": "tailwindcss",
	      	"*.css": "tailwindcss",
	      	"*.module.css": "tailwindcss"
	      },

	      // CSS Variables Settings
	      "cssVariables.lookupFiles": [
	      	"**/*.css",
	      	"**/*.scss",
	      	"**/*.sass",
	      	"**/*.less",
	      	"node_modules/open-props/open-props.min.css"
	      ],

	      // Minimap Settings
	      "editor.minimap.renderCharacters": false,
	      "editor.minimap.size": "fit",
	      "editor.minimap.enabled": false,
      	"tabnine.experimentalAutoImports": true,
	      "explorer.confirmDelete": false,
	      "terminal.integrated.fontFamily": "Iosevka",
	      "terminal.integrated.fontSize": 15,
	      "terminal.integrated.tabs.enabled": false,
	      "typescript.updateImportsOnFileMove.enabled": "always",

	      //Breadcrumbs

      	"breadcrumbs.icons": false,
	      "breadcrumbs.showKeys": false,
	      "breadcrumbs.showFiles": false,
	      "breadcrumbs.symbolPath": "off",
	      "breadcrumbs.showArrays": false,
	      "breadcrumbs.showEvents": false,
	      "breadcrumbs.showFields": false,
	      "breadcrumbs.showClasses": false,
	      "breadcrumbs.showMethods": false,
	      "breadcrumbs.showBooleans": false,
	      "breadcrumbs.showFunctions": false,
	      "breadcrumbs.showConstants": false,
	      "breadcrumbs.showEnumMembers": false,
	      "breadcrumbs.showConstructors": false,

	      //JS & TS
	      "typescript.preferences.quoteStyle": "single",
	      "javascript.preferences.quoteStyle": "single",
	      "javascript.format.semicolons": "remove",
	      "typescript.format.semicolons": "remove",
	      // Использование экспериментальных декораторов в JS/TS
	      "js/ts.implicitProjectConfig.experimentalDecorators": true,

	      "files.exclude": {
	      	"**/.expo": true,
	      	"**/.expo-shared": true,
	      	"**/.idea": true,
	      	"**/.next": true,
	      	"**/.nuxt": true,
	      	"**/dist": true
	      },

	      // Язык по умолчанию для новых файлов
	      "files.defaultLanguage": "plaintext",
      	// Игнорировать пробелы при сравнении в редакторе diff
      	"diffEditor.ignoreTrimWhitespace": false,
	      // Открытие не доверенных файлов без предупреждения
	      "security.workspace.trust.untrustedFiles": "open",
	      // Автоматически изменять предложение автозаполнения на основе предыдущего выбора
	      "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	      // Подтверждение перед закрытием окна только при использовании клавиатуры
	      "window.confirmBeforeClose": "keyboardOnly",
	      // Не открывать репозиторий в родительских папках
	      "git.openRepositoryInParentFolders": "never",
      
	      // Поведение при обнаружении нескольких определений
	      "editor.gotoLocation.multipleDefinitions": "goto",
	      // Скрыть подсказку в пустом редакторе
	      "workbench.editor.empty.hint": "hidden"
      }





      

