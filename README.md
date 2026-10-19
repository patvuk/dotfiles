# dotfiles

Configuration files and one setup script for macOS (arm64), Debian, Ubuntu,
Arch, CachyOS, and Omarchy.

## Install

```sh
git clone git@github.com:<you>/dotfiles.git ~/Developer/dotfiles
cd ~/Developer/dotfiles
./setup.sh
```

The script asks all questions at the start. Then it continues with no input.
You can run it again at any time.

Without git, download the archive for your OS from
[Releases](https://github.com/patvuk/dotfiles/releases/latest), unpack it, and
run `./setup.sh` inside `dotfiles/`. It holds only the files that OS uses.

On Omarchy, add `--no-debloat` to keep the preinstalled apps.

On Windows, `windows/setup.ps1` makes a few tweaks. See
[docs/windows.md](docs/windows.md).

## Docs

For all details, see [docs/](docs/README.md).
