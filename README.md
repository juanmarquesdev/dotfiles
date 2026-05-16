# dotfiles

Configurações pessoais gerenciadas com [GNU Stow](https://www.gnu.org/software/stow/).

## Estrutura

```
dotfiles/
  zsh/      → .zshrc, .p10k.zsh
  git/      → .gitconfig
  tmux/     → .tmux.conf
```

## Instalação em uma nova máquina

```bash
git clone git@github.com:juanmarquesdev/dotfiles.git ~/dotfiles
cd ~/dotfiles
stow zsh git tmux
```