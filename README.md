# Restore Imported Names for Framer

This module will restore the original names for your imported layers and remove any appended numbers, underscores etc.

#### Installation
1. Add restoreImportedNames.coffee to your project's /modules folder
2. Include the module after you've imported your layers

```coffeescript
sketch = Framer.Importer.load("imported/myproject")

restore = require 'restoreImportedNames'
restore()
```