<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/tmux/tmux">Tmux</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>
<h4 align="center">
⚠️  This is a custom fork of the <a href=https://github.com/catppuccin/tmux>original catppuccin theme</a>
</h4>

<p align="center">
  <img src="./.github/images/screenshot.png"/>
</p>

## Usage

### TPM

1. Install [TPM](https://github.com/tmux-plugins/tpm)
2. Add the Catppuccin plugin:

```bash
set -g @plugin 'pauchiner/catppuccin-theme'
# ...alongside
set -g @plugin 'tmux-plugins/tpm'
```

#### Configuration options

the theme support certain levels of customization, To add these customizations, add any of the following
options to your Tmux configuration.

> ⚠️ In order to have the correct icons displayed please use your favorite nerd fonts patched font.

##### Disable window tabs

By default, the theme places the `window-status` in the `status-left`. With
`@catppuccin_window_tabs_enabled` set to `on`, the theme will place the
directory within the `status-left` and move the window names to the
`window-status` format variables.

```sh
set -g @catppuccin_window_tabs_enabled on # or off to disable window_tabs
```

##### Configure separator

By default, the theme will use a round separator for left and right.
To overwrite it use `@catppuccin_left_separator` and `@catppuccin_right_separator` 

```sh
set -g @catppuccin_left_separator "█"
set -g @catppuccin_right_separator "█"
```

##### Enable DateTime

By default, the `date_time` component is set to off.
It can be enabled by specifying any tmux date and time format.

```sh
set -g @catppuccin_date_time "%Y-%m-%d %H:%M"
```

##### Enable User

By default, the `user` component is set to off.
It can be enabled by toggling it on.

```sh
set -g @catppuccin_user "on"
```

##### Enable Host

By default, the `host` component is set to off.
It can be enabled by toggling it on.

```sh
set -g @catppuccin_host "on"
```

##### Customize Icons

Each of the components comes with their own default icon, which
can be changed to fit your preference or requirements of your font.

*Note: NerdFont Icons do not render properly in the Github UI, so the below example
does not use them*
```sh
set -g @catppuccin_datetime_icon "A"
set -g @catppuccin_user_icon "B"
set -g @catppuccin_directory_icon "C"
set -g @catppuccin_window_icon "D"
set -g @catppuccin_session_icon "E"
set -g @catppuccin_host_icon "F"
```

## 💝 Thanks to

- [Pocco81](https://github.com/catppuccin)
- [vinnyA3](https://github.com/vinnyA3)
- [rogeruiz](https://github.com/rogeruiz)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
