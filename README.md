# reformat_json
This Repo is for generating the dart class from the json file

**What your code correctly does:**
Uses jsoneditor to allow JSON view/edit with error handling.

Implements autoRepair with regex enhancements to:

Quote unquoted keys.

Quote unquoted string values heuristically.

Remove trailing commas.

Provides buttons for format, auto repair, generate Dart model, and copy Dart code.

Allows user to input a custom root class name for Dart model.

Generates Dart classes preserving parent-before-child hierarchy.

Uses good Dart typing decisions (nullables, Lists, primitives).

Shows messages on success/failure.

Copies Dart code to clipboard and resets message smoothly.
