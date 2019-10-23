# ERB-VSCode-Snippets

This extension is a fork of [ERB-VSCode-Snippets](https://github.com/ZneuRay/ERB-VSCode-Snippets) which is a fork of [ERB-Sublime-Snippets](https://github.com/matthewrobertson/ERB-Sublime-Snippets)

A collection of [Visual Studio Code](https://code.visualstudio.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

## Version

_0.0.5_ - New helpers (cloudinary image tag, time ago in words, simple form, etc.)

_0.0.3 ~ 0.0.4_ - Syntax fixed

_0.0.2_ - First release

## Features

![feature](images/feature.gif?raw=true)

## Installation

These snippets can now be installed via [VS Code Marketplace](https://marketplace.visualstudio.com/VSCode).

<!-- ## Manual installation with extension

1. Download [erb-vscode-snippets.vsix](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/bin/erb-vscode-snippets.vsix)
2. Press `F1` enter `ext vsix`
3. Select `erb-vscode-snippets.vsix` -->

## Manual installation without extension

1. You can just copy the snippets from [snippets.json](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/snippets/snippets.json)
2. Go to `Preferences > User Snippets` and enter `erb`
3. Paste the snippets code

## Snippets and Bindings

| Snippet                               | Tab Trigger | Output                              |
| ------------------------------------- | ----------- | ----------------------------------- |
| ERB comment tag                       | **pc**      | `<%# %>`                            |
| `each` helper                         | **each**    | `<% @things.each do |thing| %> ...` |
| `else` tag                            | **else**    | `<% else %>`                        |
| `elsif` tag                           | **elsif**   | `<% elsif %>`                       |
| `end` tag                             | **end**     | `<% end %>`                         |
| ERB no display tag                    | **er**      | `<% %>`                             |
| `form_for` helper                     | **ff**      | `<%= form_for(@ ) do |f| %> ...`    |
| `if` / `else` block                   | **ife**     | `<% if %>...<% else %>...<% end %>` |
| `if` block                            | **if**      | `<% if %>...<% end %>`              |
| `label_tag` helper                    | **lblt**    | `<%= label_tag ..., ... %>`         |
| `link_to` helper                      | **lt**      | `<%= link_to ..., ... %>`           |
| ERB display tag                       | **pe**      | `<%= %>`                            |
| `submit_tag` helper                   | **st**      | `<%= submit_tag ..., ... %>`        |
| `text_field_tag` helper               | **tft**     | `<%= text_field_tag ..., ... %>`    |
| `unless` block                        | **unless**  | `<% unless %>...<% end %>`          |
| `image_tag` helper                    | **it**      | `<%= image_tag ..., ... %>`         |
| `cl_image_tag` helper                 | **clt**     | `<%= cl_image_tag(...) %>`          |
| `time_ago_in_words` helper            | **tw**      | `<%= time_ago_in_words(...) %>`     |
| `simple_form_for` helper              | **sf**      | `<%= simple_form_for ... do |f| %>` |
| `f.input` helper tag for simple form  | **fi**      | `<%= f.input ... %>`                |
| `hidden_field_tag` helper tag         | **hft**     | `<%= hidden_field_tag ..., ... %>`  |
| `f.submit` helper tag for simple form | **ft**      | `<%= f.submit ... %>`               |

## License

Released under [WTFPL, Version 2](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/LICENSE.txt)
