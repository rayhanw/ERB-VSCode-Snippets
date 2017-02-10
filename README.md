# ERB-VSCode-Snippets
====================

This extension is a fork of [ERB-Sublime-Snippets](https://github.com/matthewrobertson/ERB-Sublime-Snippets)

A collection of [Visual Studio Code](https://code.visualstudio.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

## Features

![feature](images/feature.gif?raw=true)

## Installation

These snippets can now be installed via [VS Code Marketplace](https://marketplace.visualstudio.com/VSCode).

## Manual installation with extension

1. Download [erb-vscode-snippets.vsix](https://raw.githubusercontent.com/ZneuRay/ERB-VSCode-Snippets/master/bin/erb-vscode-snippets-0.0.1.vsix)
2. Press `F1` enter `ext vsix`
3. Select `erb-vscode-snippets.vsix`
  
## Manual installation without extension

1. You can just copy the snippets from [snippets.json](https://raw.githubusercontent.com/ZneuRay/ERB-VSCode-Snippets/master/snippets/snippets.json)
2. Go to `Preferences > User Snippets` and enter `erb`
3. Paste the snippets code

## Snippets and Bindings

<table>
  <tr>
    <th>Snippet</th>
    <th>Tab Trigger</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>ERB tags</td>
    <td>__er__</td>
    <td>`<%  %>`</td>
  </tr>
  <tr>
    <td>print ERB tags</td>
    <td>__pe__</td>
    <td>`<%=  %>`</td>
  </tr>
  <tr>
    <td>print ERB comment</td>
    <td>__pc__</td>
    <td>`<%#  %>`</td>
  </tr>
  <tr>
    <td>`if` block</td>
    <td>__if__</td>
    <td>`<% if  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`if` / `else` block</td>
    <td>__ife__</td>
    <td>`<% if  %>...<% else %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`else` tag</td>
    <td>__else__</td>
    <td>`<% else %>`</td>
  </tr>
  <tr>
    <td>`elsif` tag</td>
    <td>__elsif__</td>
    <td>`<% elsif %>`</td>
  </tr>
  <tr>
    <td>`unless` block</td>
    <td>__unless__</td>
    <td>`<% unless  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`end` block</td>
    <td>__end__</td>
    <td>`<% end %>`</td>
  </tr>
  <tr>
    <td>`submit_tag` helper</td>
    <td>__st__</td>
    <td>`<%= submit_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`text_field_tag` helper</td>
    <td>__tft__</td>
    <td>`<%= text_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`password_field_tag` helper</td>
    <td>__pft__</td>
    <td>`<%= password_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`label_tag` helper</td>
    <td>__lblt__</td>
    <td>`<%= label_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`link_to` helper</td>
    <td>__lt__</td>
    <td>`<%= link_to ..., ... %>`</td>
  </tr>
  <tr>
    <td>`each` helper</td>
    <td>__each__</td>
    <td>`<% @things.each do |thing| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`form_for` helper</td>
    <td>__ff__</td>
    <td>`<%= form_for(@ ) do |f| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`t()` helper</td>
    <td>__t__</td>
    <td>`<%= t('@') %>`</td>
  </tr>
<table>

## License

Released under [WTFPL, Version 2](https://raw.githubusercontent.com/ZneuRay/ERB-VSCode-Snippets/master/LICENSE.txt)
