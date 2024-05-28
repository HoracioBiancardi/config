
dependencias
```bash
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl git \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```


instalação automatica
```bash
curl https://pyenv.run | bash
```


for zsh

```bash
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo '[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
```

python global
```
pip install pipx
```

depois e so instalar as biblioteca que vc quer por padrao
```
pipx install poetry

pipx ensurepath
```




```
poetry config --list
poetry config virtualenvs.in-project true

```

```
pip freeze | grep -v "^-e" | xargs pip uninstall -y

```
