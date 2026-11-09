```powershell
nvidia-smi
```


```powershell
uv init --bare --python 3.14.0
uv sync
```

```powershell
uv run python -c "import torch; print(torch.__version__); print(torch.version.cuda); print(torch.cuda.is_available())"
```

```
ruff check --fix my_notebook.ipynb
ruff format my_notebook.ipynb
```