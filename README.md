<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://st.suckless.org/">st</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/st/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/st?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/st/issues"><img src="https://img.shields.io/github/issues/catppuccin/st?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/st/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/st?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="assets/banner.webp"/>
</p>

## Previews
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>

## About

This port offers the colors needed for ST's header files, but **not an ST build**.

## Usage

1. Choose your flavour.
2. Copy the contents of `macchiato.h` and replace into your st build's `config.h`.

```bash
gh repo clone m-c-frank/sttheme
cd sttheme
cp macchiato.h ~/.local/src/st/config.def.h
cd ~/.local/src/st/
sudo rm config.h
sudo make clean
sudo make install
```

4. Then `make install` it in st folder.

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
