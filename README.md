# Dotfiles

个人使用的配置文件。

> 前置条件是安装了`yay`，无论是archlinuxcn里面的，还是make的都行。

以下是文件说明：

- `install_all`：安装文件，会提示输入`Y`/`y`来确认安装某模块。
- `install_fcitx5`：安装fcitx5和相关中文扩展。
- `install_font`：安装字体，前面一堆文泉驿等等字体都是针对中文而安装，`ttf-cascadia-code`是微软的开源字体，是“Windows终端”软件里的默认字体，感觉中英文支持还不错，设置为 alacritty 的默认字体了。
- `install_hypr`：**重点** 安装Hyprland、swww、alacritty、wofi、thunar、wlogout、waybar等等
- `install_zsh`：安装zsh wget curl等等，这部分需要能`clone` Github的项目下来，可能需要一些Proxy。

以下是一些软件说明：

- hyprland：桌面
- alacritty：终端
- wofi：应用启动器
- thunar：文件管理
- nemo：文件管理，会给thunar添加挂载功能，界面没thunar好看
- grim：截图工具
- slurp：帮助截图工具的，用于选择一个区域截图
- swappy：图片编辑器
- swayimg：图片查看
- waybar-hyprland：waybar的hyprland支持
- swww：设置壁纸
- wlogout：注销菜单，有退出登录、重启、关机、锁屏那个
- swaylock-effects：锁屏，swaylock的fork版本，添加了一些额外视觉效果
- pulseaudio：音频支持
- pamixer：音频支持
- pulseaudio-alsa：音频支持
- alsa-utils：音频支持
- pavucontrol：用于在waybar中滚轮调整音量
- polkit-gnome：GUI程序用于获取权限的提示输入框
- otf-font-awesome：图标字体
- brightnessctl：控制显示器亮度
- qt5-wayland：qt支持
- qt6-wayland：qt支持
- xdg-desktop-portal-hyprland-git：Hyprland 的 xdg-desktop-portal

以下是部分问题（仅我遇到）：
- 输入法问题，JetBrains系列软件无法使用输入法，chromium也用不了，静等修复，但是vscode、火狐等可以用。
- 软件通知，hyprland官方wiki有说，使用`dunst`/`mako`等等，我这里有配置文件，但是我用不上。
- 网络，使用的是Clash For Windows的linux版本，来科学上网。

预览截图在`screenshots`文件夹下。
> 截图中出现的软件：YesPlayMusic(音乐播放器,yay源)、cava(音频可视化，pacman源)、bottom(性能查看，pacman源)