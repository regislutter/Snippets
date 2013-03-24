Snippets
========

Multiple snippets for Sublime Text 2

##Installation

First, you need a copy of [Sublime Text 2].

###Linux

Download the *PHP-codeigniter.sublime-completions* file up above, and drop it in your *~/.config/sublime-text-2/Packages/PHP/* folder. Should work immediately.

OR

With command line :

    $ cd ~/.Sublime Text 2/Packages/
    $ git clone git://github.com/zetura/Snippets.git Snippets

###Mac OS X

Download the *PHP-codeigniter.sublime-completions* file up above, and drop it to *%appdata%\Sublime Text 2\Packages\PHP\* folder. Should work immediately
You need also access to your library, type this command line in the Terminal :

    $ chflags nohidden ~/Library/

OR

With command line :

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/zetura/Snippets.git Snippets

###Windows

Download the *PHP-codeigniter.sublime-completions* file up above, and drop it to *%appdata%\Sublime Text 2\Packages\PHP\* folder. Should work immediately

OR

With command line :

    $ cd %APPDATA%/Sublime Text 2/Packages/
    $ git clone git://github.com/zetura/Snippets.git Snippets

## Snippets and Bindings

<table>
  <tr>
    <th>Snippet</th>
    <th>Tab Trigger</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>Audio player</td>
    <td>audio</td>
    <td>Some buttons to play/pause and change the volume of a MP3 file in HTML5</td>
  </tr>
  <tr>
    <td>Video player</td>
    <td>video</td>
    <td>Generate a HTML5 video tag to play a MP4 or OGG file. If the browser don't use HTML5, the video player switch on a flash player.</td>
  </tr>
  <tr>
    <td>Context menu</td>
    <td>contextmenu</td>
    <td>A context menu to manage right click on elements</td>
  </tr>
  <tr>
    <td>HTML5 Content</td>
    <td>html5</td>
    <td>The default content of a HTML5 page (section, articles, aside and footer). Combine it with the HTML5 structure below.</td>
  </tr>
  <tr>
    <td>HTML5</td>
    <td>html5</td>
    <td>The structure of a default HTML5 page (Doctype, head, meta, stylesheet, etc.)</td>
  </tr>
  <tr>
    <td>Hidden p</td>
    <td>hidden</td>
    <td>p hidden>You can't see this text</p</td>
  </tr>
  <tr>
    <td>Autofocus input</td>
    <td>input</td>
    <td>input autofocus="autofocus"</td>
  </tr>
  <tr>
    <td>Data list</td>
    <td>input</td>
    <td>A dropdown list with autocompletion in HTML5</td>
  </tr>
  <tr>
    <td>Email input</td>
    <td>input</td>
    <td>input type="email" pattern="[^ @]*@[^ @]*" value=""</td>
  </tr>
  <tr>
    <td>Password input</td>
    <td>input</td>
    <td>input title="at least eight symbols containing at least one number, one lower, and one upper letter" type="text" pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{8,}" required</td>
  </tr>
  <tr>
    <td>Phone input</td>
    <td>input</td>
    <td>input type="text" required pattern="(\+?\d[- .]*){7,13}" title="international, national or local phone number"</td>
  </tr>
  <tr>
    <td>Email in text input</td>
    <td>input</td>
    <td>input type="text" title="email" required pattern="[^@]+@[^@]+\.[a-zA-Z]{2,6}"</td>
  </tr>
  <tr>
    <td>URL input</td>
    <td>input</td>
    <td>input type="url" value=""</td>
  </tr>
</table>

##Questions, Comments, Concerns?

Feel free to submit a pull request with any snippets you would like to add to the project. If you have any problems or suggestions you can contact me [on twitter](https://twitter.com/regislutter).

[Sublime Text 2]: http://www.sublimetext.com/2
