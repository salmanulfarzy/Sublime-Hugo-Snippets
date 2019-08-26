# Sublime Text Snippets for [Hugo](https://gohugo.io)

## Installation

### OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
    $ git clone git@github.com:salmanulfarzy/Sublime-Hugo-Snippets.git

### Linux (Ubuntu like distros)

    $ cd ~/.config/sublime-text-3/Packages/User
    $ git clone git@github.com:salmanulfarzy/Sublime-Hugo-Snippets.git

## Available Snippets

| Snippet      | Tab Trigger | Output                             |
| ------------ | ----------- | ---------------------------------- |
| Curlies      | **x**       | `{{ }}`                            |
| Dot          | **dot**     | `{{ . }}`                          |
| If           | **if**      | `{{ if }} {{ end }}`               |
| If/Else      | **ife**     | `{{ if }} {{ else }} {{ end }}`    |
| If/Else if   | **ifei**    | `{{ if }} {{ else if }} {{ end }}` |
| With         | **with**    | `{{ with }} {{ end }}`             |
| With/Else    | **withe**   | `{{ with }} {{ else }} {{ end }}`  |
| Range        | **range**   | `{{ range }} {{ end }}`            |
| Partial      | **partial** | `{{ partial "" . }}`               |
| Shortcode    | **partial** | `{{< >}}`                          |
| Block        | **block**   | `{{ block "main" . }} {{ end }}`   |
| Block define | **define**  | `{{ define "block" }} {{ end }}`   |
| Variable     |  **vars**   | `{{ $var := what }}`               |
| Debug        |  **debug**  | `{{ printf "%#v" }}`               |
| Comment      |  **comm**   | `{{/* */}}`                        |
