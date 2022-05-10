### Agregar virtualenv como nuevo kernel
```shell
poetry install
poetry shell
ipython kernel install --name "nuevo-kernel" --user
```
No olvidar el `--user`. Es mucho muy importante.
