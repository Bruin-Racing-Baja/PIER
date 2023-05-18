# PIER
Protofile Internal Educational Repository

This repository is meant to be added as a submodule in order to keep the different proto files orgainized and insulated from other changes.

When changing protos, old enumerations should not be used, even if what was being logged to them is removed. This ensures backwards-compatability with generated files and data analysis tools