# lotsofpeople-import-behavior
Behavior for propagating content of markdown files to Polymer properties

Use behavior in Polymer elements as:


> function set(path, file) {
>          var filePath = "/content/" + file
>          self._getImportContents(filePath, function(content) {
>            self.set(path, content)
>          })
>        }
>
> set('introHeader', 'intro-header.md')


