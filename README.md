This plugin introduces LaTeX compilation to the [Cloud9 IDE](https://github.com/ajaxorg/cloud9)

Installation
------------

Checkout the Cloud9 repository from https://github.com/ajaxorg/cloud9.
From the Cloud9 directory, run
   
    git submodule add git://github.com/scribtex/cloud9-latex-plugin.git client/ext/latex

You also need to add "ext/latex/compile" to the `Ide.DEFAULT_PLUGINS` list in
server/cloud9/ide.js, or otherwise manually enable the plugin.
