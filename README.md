## Tips

### Installere pip
```bash
paru
paru -S python-pip
```

### Installere jupyterlab
```bash
paru jupyterlab
```
Velg 1

> Hvis det gir feilmelding prøv `pip3 install jupyterlab`

### Legge til jupyter i path (valgfri)
> Hvis man kun installerer jupyter fra pip
```bash
echo "export PATH=\"\$PATH:$HOME/.local/bin/\"" >> ~/.zshrc
source ~/.zshrc
```

# Installer og kjør Jupyterlab

```bash
pip install jupyterlab (Hvis ikke allerede installert i forrige steg)
jupyter serverextension enable --py jupyterlab --sys-prefix
jupyter lab
```
Hvis dette ikke fungerer, bytt ut "jupyter" med `python3 -m jupyter`
```bash
python3 -m jupyter serverextension enable --py jupyterlab --sys-prefix
python3 -m jupyter lab
```
evt. med py launcher for Windows:
```bash
py -3 -m jupyter serverextension enable --py jupyterlab --sys-prefix
py -3 -m jupyter lab
```
