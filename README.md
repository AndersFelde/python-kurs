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
