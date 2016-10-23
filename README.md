# Restore Imported Names for Framer

This module will restore the original names for your imported layers and remove any appended numbers, underscores etc.

#### How to use
```coffeescript
sketch = Framer.Importer.load("imported/myproject")

restore = require 'restoreImportedNames'
restore()
```