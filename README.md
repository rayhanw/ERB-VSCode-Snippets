# ERB-VSCode-Snippets
====================

This extension is a fork of [ERB-Sublime-Snippets](https://github.com/matthewrobertson/ERB-Sublime-Snippets)

A collection of [Visual Studio Code](https://code.visualstudio.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

## Version

*0.0.3 ~ 0.0.4* - Syntax fixed

*0.0.2* - First release

## Features

![feature](images/feature.gif?raw=true)

## Installation

These snippets can now be installed via [VS Code Marketplace](https://marketplace.visualstudio.com/VSCode).

## Manual installation with extension

1. Download [erb-vscode-snippets.vsix](https://raw.githubusercontent.com/ZneuRay/ERB-VSCode-Snippets/master/bin/erb-vscode-snippets.vsix)
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
    <td>ERB comment tag</td>
    <td>**pc**</td>
    <td>`<%#  %>`</td>
  </tr>
  <tr>
    <td>`each` helper</td>
    <td>each</td>
    <td>`<% @things.each do |thing| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`else` tag</td>
    <td>**else**</td>
    <td>`<% else %>`</td>
  </tr>
  <tr>
    <td>`elsif` tag</td>
    <td>**elsif**</td>
    <td>`<% elsif %>`</td>
  </tr>
  <tr>
    <td>`end` block</td>
    <td>**end**</td>
    <td>`<% end %>`</td>
  </tr>
  <tr>
    <td>ERB no display tag</td>
    <td>**er**</td>
    <td>`<%  %>`</td>
  </tr>
  <tr>
    <td>`form_for` helper</td>
    <td>ff</td>
    <td>`<%= form_for(@ ) do |f| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`if` / `else` block</td>
    <td>**ife**</td>
    <td>`<% if  %>...<% else %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`if` block</td>
    <td>**if**</td>
    <td>`<% if  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`label_tag` helper</td>
    <td>lblt</td>
    <td>`<%= label_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`link_to` helper</td>
    <td>lt</td>
    <td>`<%= link_to ..., ... %>`</td>
  </tr>
  <tr>
    <td>print ERB tags</td>
    <td>**pe**</td>
    <td>`<%=  %>`</td>
  </tr>
  <tr>
    <td>`submit_tag` helper</td>
    <td>**st**</td>
    <td>`<%= submit_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`text_field_tag` helper</td>
    <td>**tft**</td>
    <td>`<%= text_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`unless` block</td>
    <td>**unless**</td>
    <td>`<% unless  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`cl_image_tag` helper</td>
    <td>**clt**</td>
    <td>`<%= cl_image_tag(...) %>"`</td>
  </tr>
  <tr>
    <td>`time_ago_in_words` helper</td>
    <td>**tw**</td>
    <td>`time_ago_in_words(...)`</td>
  </tr>
<table>

## License

Released under [WTFPL, Version 2](https://raw.githubusercontent.com/ZneuRay/ERB-VSCode-Snippets/master/LICENSE.txt)
