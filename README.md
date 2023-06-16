# GGLO-Toolbar

The GGLO Toolbar is a pyRevit extension, and is built on version 4.8.13, which is compatible with Revit 2024.
  https://github.com/eirannejad/pyRevit

The following method can be used to avoid installing pyRevit via the Settings menu from within Revit itself, and might be beneficial to automate company related installation process' as well. Thanks to Jean-Marc Couffin for suggesting/helping write this section!

# Directly installing the GGLO-Toolbar
Install pyRevit from https://github.com/eirannejad/pyRevit/releases
WIN+R, then type 'cmd'
In the command line, install the extension with the following command:
*****************
pyrevit extend ui GGLO-Toolbar https://github.com/sburkeGGLO/GGLO-Toolbar.git --dest="C:\\_GGLO\RevitTools" --branch=main
***************** 
  If Revit was opened, use the reload button of pyRevit
