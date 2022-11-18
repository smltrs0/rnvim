# rnvim
Custom neovim configuration

### Test it on a Docker container

```console
docker run -w /root -it --rm alpine:edge sh -uelic '
apk add git nodejs neovim ripgrep alpine-sdk --update
git clone https://github.com/mrroiz/rnvim ~/.config/nvim
nvim'
```
