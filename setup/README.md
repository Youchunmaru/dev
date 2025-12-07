# setup

```bash
sudo apt-get/dnf install /pacman -S python3
```

```bash
python -m ensurepip --upgrade
```

```bash
pip install ansible
```

```bash
ansible-playbook setup.yml --ask-become-pass
```

## ubuntu

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
brew install lazydocker lazygit gopass lf eza btop
```

## arch

```bash
pip install -U pgcli 'mycli[all]'

```

```bash
pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

## common

```bash
curl https://mise.run | sh
```
