# zsh-pnpm

![Version](https://img.shields.io/badge/version-1.3.0-brightgreen)
![License](https://img.shields.io/github/license/zfben/zsh-pnpm)

A zsh plugin for using `p` as `pnpm` aliases and more.

| Alias | Command
| --- | ---
| `p` | `pnpm`
| `pi` | `pnpm install`
| `pu` | `pnpm update`
| `pr` | `pnpm run`
| `pe` | `pnpm exec`
| `pb` | `pnpm run build`
| `pd` | `pnpm run dev`
| `pt` | `pnpm run test`
| `ps` | `pnpm run start`
| `pl` | `pnpm run lint`
| `po` | `pnpm outdated`
| `px` | `pnpm dlx`

## Install

### Manual

```zsh
git clone --depth=1 https://github.com/zfben/zsh-pnpm.git ~/.zsh-pnpm
echo 'source ~/.zsh-pnpm/zsh-pnpm.plugin.zsh' >>~/.zshrc
```

### Using [oh-my-zsh](https://github.com/ohmyzsh/oh-my-zsh)

Execute `git clone --depth=1 https://github.com/zfben/zsh-pnpm.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-pnpm`. Add `zsh-pnpm` into plugins array in `.zshrc`
