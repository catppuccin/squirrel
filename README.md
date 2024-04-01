<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/rime/squirrel">Squirrel(Rime for MacOS)</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/moseeking/squirrel/stargazers"><img src="https://img.shields.io/github/stars/moseeking/squirrel?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/moseeking/squirrel/issues"><img src="https://img.shields.io/github/issues/moseeking/squirrel?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/moseeking/squirrel/contributors"><img src="https://img.shields.io/github/contributors/moseeking/squirrel?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="./assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="./assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="./assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="./assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="./assets/mocha.webp"/>
</details>

&nbsp;

> Read this in other languages: [English](./README.md),[简体中文](./README.zh-cn.md).

## Usage

1. Download `squirrel.custom.yaml` file [here](./theme/squirrel.custom.yaml).
2. Open the `Squirrel` configuration folder through the `Settings...` menu item in the `Squirrel` menu bar.
3. Backup the `squirrel.custom.yaml` file in the configuration folder,replace it with the `squirrel.custom.yaml` file downloaded in step one.
> Instead: open the `squirrel.custom.yaml` file under the configuration folder, copy the content after the `preset_color_schemes` tag from the downloaded file in step one into the configuration, and modify the content of the `style/color_scheme` and `style/color_scheme_dark` tags to your preferred theme. This ensures that the original configuration content is preserved to the greatest extent possible. For specific parameters, please refer to the FAQ.  
4. Make the configuration effective through the `Deploy` menu item in the `Squirrel` menu bar (default shortcut: control+option+\`).
5. Well done,Enjoy~


<!-- this section is optional -->
## 🙋 FAQ

### How to customize the related color theme?
The following are some custom theme parameters within the file `squirrel.custom.yaml`：
```
  style/color_scheme: catppuccin_latte         # for MacOS Light Appearance
  style/color_scheme_dark: catppuccin_mocha    # for MacOS Dark Appearance
```
Here are some color parameters for custom themes(`#aabbggrr`)：
``` 
  back_color: 0xFFFFFF                         # Candidate bar background color
  border_color: 0xFFFFFF                       # Border color
  text_color: 0xFFFFFF                         # Pinyin line text color 
  label_color: 0xFFFFFF                        # Candidate bar number color
  candidate_text_color: 0xFFFFFF               # Candidate item text color
  hilited_back_color: 0xFFFFFF                 # Background color of the first candidate item
  hilited_candidate_text_color: 0xFFFFFF       # Text color of the first candidate item
  hilited_candidate_label_color: 0xFFFFFF      # Number color of the first candidate item
  hilited_text_color: 0xFFFFFF                 # Highlighted Pinyin (requires embedded coding)
  hilited_comment_text_color: 0xFFFFFF         # Highlighted annotation text color
  comment_text_color: 0xFFFFFF                 # Pinyin and other prompt text color
```
> Tip:the color format for Squirrel is `#aabbggrr`. If using a different color format, please make sure to replace accordingly.

### Can this configuration be adapted to other platforms of Rime input method? 
> As for other Rime input methods on different platforms, such as [Weasel](https://github.com/rime/weasel), they should be compatible according to Rime's instructions. You just need to rename the configuration file to the `<configuration code>.custom.yaml`,this project has not undergone relevant testing. Please refer to the [Rime official documentation](https://github.com/rime/home/wiki ) for details.


## 💝 Thanks to

- [moseeking](https://github.com/moseeking)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
