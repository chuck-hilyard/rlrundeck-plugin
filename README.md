suite of tools built for use as Rundeck "plugins"

Rundeck plugin developer guide -> http://rundeck.org/docs/developer/plugin-development.html

rake this area to build the plugin format for rundeck use


Directory structure
[name]-plugin.zip
\- [name]-plugin/ -- root directory of zip contents, same name as zip file
   |- plugin.yaml -- plugin metadata file
      \- contents/
            |- ...      -- script or resource files
                  \- ...
