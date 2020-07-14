# Mocha - Indexiine

## SD 卡准备 {docsify-ignore}

我们现在需要把一些 CFW 需要使用到的文件放进你的 SD 卡。

?> **注意** 你的 SD 卡需要被格式化为 FAT32。 如果你的 SD 卡没有格式化为 FAT32，则你需要用 [GUIFormat](http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm) 格式化，并将分配单元大小设置为 32k（32768）。

### What You Need {docsify-ignore}

- Mocha <a href="docs/files/config.ini" download>配置文件</a>。
- 最新版 [Homebrew Launcher Installer](https://github.com/wiiu-env/homebrew_launcher_installer/releases/latest)。
  - 你需要下载 `payload.zip` 文件。
- 1.4 版的 [The Homebrew Launcher](https://github.com/dimok789/homebrew_launcher/releases/tag/1.4)。
  - 你需要下载 v1.4 `homebrew_launcher.v1.4.zip` 的 Homebrew Launcher。
- 最新版 [WUP Installer GX2](http://wiiubru.com/appstore/zips/wup_installer_gx2.zip)。
- 最新版 [Wii U NAND Dumper](https://github.com/koolkdev/wiiu-nanddumper/releases/latest)。
- 最新版 [Homebrew App Store](https://github.com/vgmoose/hbas/releases/latest)。
  - 你需要下载 `wiiu-extracttosd.zip` 文件。
- 最新版 [Mocha](https://www.wiiubru.com/appstore/zips/mocha.zip)。
- 最新版 <a href="docs/files/SaveMii_Mod.zip" download>SaveMii Mod</a>。
- 最新版 [Indexiine-Installer](https://github.com/GaryOderNichts/indexiine-installer/releases/latest)。

### Instructions {docsify-ignore}

?> **注意** info.json 和 manifest.install 文件在破解过程中是不需要的，可以删除。

1. 将你的 Wii U SD 卡 插入你的电脑。
1. 解压 `wup_installer_gx2.zip` 到你的 SD 卡根目录。
1. 解压 `nanddumper.zip` 到你的 SD 卡根目录。
1. 解压 `wiiu-extracttosd.zip` 到你的 SD 卡根目录。
1. 解压 `homebrew_launcher.v.1.4.zip` 到你的 SD 卡根目录。
1. 解压 `mocha.zip` 到你的 SD 卡根目录。
1. 解压 `indexiine-installer.zip` 到你的 SD 卡根目录。
1. 解压 `savemii_mod.zip` 到你 SD 卡的根目录。
1. 复制 `config.ini` 到 SD 卡的 `/wiiu/apps/mocha` 文件夹下。
1. 从 `payload.zip` 中解压 `payload.elf` 到 SD 卡根目录下的 `wiiu` 文件夹中。