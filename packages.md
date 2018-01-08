# Packages

## SFTP-deployment

## Sublime-Style-Column-Selection

## atom-alignment

## atom-clock

## atom-terminal

## autoclose-html

## autocomplete-paths

## busy-signal

## color-picker

## custom-title

タイトルバーにファイルのパス他を表示する

```js
<% if (projectPath) { %>
	<%= projectName %>
	 <% if (relativeFilePath) { %>
	- <%= relativeFilePath %>
	<% } else { %>
	- <%= fileName %>
	<% } %>
<% } else { %>
	<%= filePath %>
<% } %>
<% if (gitHead) { %> [@<%= gitHead %>]<% } %>
```
- project管理下ならプロジェクト名と相対パス表示
- git管理下ならheadブランチ表示


## editorconfig

## emmet

## file-icons

## highlight-selected

## intentions

## linter

## linter-coffeelint

## linter-csslint

## linter-htmlhint

## linter-jshint

## linter-php

## linter-ruby

## linter-scss-lint

## linter-ui-default

## merge-conflicts

## minimap

minimapを表示

## minimap-autohide

minimapを非表示(スクロール時に表示)


## minimap-highlight-selected


## minimap-pigments


## monokai

theme

## open-terminal-here

> [open-terminal-here](https://atom.io/packages/open-terminal-here)

- `ctrl` + `cmd` + `T` : Open the Terminal in the current directory


## pigments


## project-manager


## sort-lines


## sync-settings


## tablr


## teletype


## terminal-plus


## trailing-spaces


## vim-mode-plus
