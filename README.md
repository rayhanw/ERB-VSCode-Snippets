# ERB-VSCode-Snippets

====================

This extension is a fork of [ERB-VSCode-Snippets](https://github.com/ZneuRay/ERB-VSCode-Snippets) which is a fork of [ERB-Sublime-Snippets](https://github.com/matthewrobertson/ERB-Sublime-Snippets)

A collection of [Visual Studio Code](https://code.visualstudio.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

## Version

*0.0.5* - New helpers (cloudinary image tag, time ago in words, simple form, etc.)

*0.0.3 ~ 0.0.4* - Syntax fixed

*0.0.2* - First release

## Features

![feature](images/feature.gif?raw=true)

## Installation

These snippets can now be installed via [VS Code Marketplace](https://marketplace.visualstudio.com/VSCode).

## Manual installation with extension

1. Download [erb-vscode-snippets.vsix](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/bin/erb-vscode-snippets.vsix)
2. Press `F1` enter `ext vsix`
3. Select `erb-vscode-snippets.vsix`

## Manual installation without extension

1. You can just copy the snippets from [snippets.json](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/snippets/snippets.json)
2. Go to `Preferences > User Snippets` and enter `erb`
3. Paste the snippets code

## Snippets and Bindings
| Snippet                              | Tab Trigger | Output                                         |
| ------------------------------------ | ----------- | ---------------------------------------------- |
| ERB comment tag                      | __pc__      | `<%#  %>`                                      |
| `each` helper                        | __each__    | `<% @things.each do |thing| %> ... <% end %>`  |
| `else` tag                           | __else__    | `<% else %>`                                   |
| `elsif` tag                          | __elsif__   | `<% elsif %>`                                  |
| `end` tag                            | __end__     | `<% end %>`                                    |
| ERB no display tag                   | __er__      | `<%  %>`                                       |
| `form_for` helper                    | __ff__      | `<%= form_for(@ ) do |f| %> ... <% end %>`     |
| `if` / `else` block                  | __ife__     | `<% if  %>...<% else %>...<% end %>`           |
| `if` block                           | __if__      | `<% if  %>...<% end %>`                        |
| `label_tag` helper                   | __lblt__    | `<%= label_tag ..., ... %>`                    |
| `link_to` helper                     | __lt__      | `<%= link_to ..., ... %>`                      |
| ERB display tag                      | __pe__      | `<%=  %>`                                      |
| `submit_tag` helper                  | __st__      | `<%= submit_tag ..., ... %>`                   |
| `text_field_tag` helper              | __tft__     | `<%= text_field_tag ..., ... %>`               |
| `unless` block                       | __unless__  | `<% unless  %>...<% end %>`                    |
| `image_tag` helper                   | __it__      | `<%= image_tag ..., ... %>`                    |
| `cl_image_tag` helper                | __clt__     | `<%= cl_image_tag(...) %>`                     |
| `time_ago_in_words` helper           | __tw__      | `<%= time_ago_in_words(...) %>`                |
| `simple_form_for` helper             | __sf__      | `<%= simple_form_for ... do |f| ... <% end %>` |
| `f.input` helper tag for simple form | __fi__      | `<%= f.input ... %>`                           |
| `hidden_field_tag` helper tag        | __hft__     | `<%= hidden_field_tag ..., ... %>              |


## License

Released under [WTFPL, Version 2](https://raw.githubusercontent.com/rayhanw/ERB-VSCode-Snippets/master/LICENSE.txt)
