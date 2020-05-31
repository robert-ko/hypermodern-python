

DEBUG:
-----------------------------------------------
Needed to append src to PYTHONPATH

TOML:

when name field not equal to src/dirname

changed name to get around weird install

Needed to add packages to hypermodern-python

packages = [
 { include = "hypermodern_python", from="src" },
]


# need to escape
poetry add --dev coverage\[toml\] 

nox had to be install in separate bash shell
