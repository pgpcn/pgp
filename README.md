# PGP Tool - 中文版的 PGP 加密工具

这是一款简单安全的 PGP 密钥生成、加密、和解密工具。希望能为不懂技术的中文用户，提供简单友好、方便使用的手动信息加密方案。

众所周知，某些地区的网络环境，尤其是聊天软件中，所有的信息都被运营商监控，已经不存在能够安全传递隐秘信息的方式。翻墙使用其它安全的聊天软件，对大多数人门槛很高，而且也不存在始终稳定可靠的翻墙途径。如果只是进行少量关键信息的传输，使用 [PGP](https://en.wikipedia.org/wiki/Pretty_Good_Privacy) 工具进行手动加密，可能是更有效的方案。

网上也有很多用来手动 PGP 加密的工具，却大多数对于新人过于复杂，或者没有中文界面。所以我们创建了这个项目，把 PGP 最基本的信息加密功能提取出来，界面尽量简化，希望能为不懂技术的中文用户，提供简单、方便传播的加密工具。

## Usage

- 可以在 github 的这个项目的网站直接使用：<https://pgpcn.github.io/pgp/>
- 项目可以被直接部署在任何网络服务器，直接复制文件到相应的根目录或子目录即可。如果所在的网络服务器不需要翻墙访问，那么，这个工具也可以不经过翻墙使用。
- 也可以将整个项目的打包 .zip 文件，下载到电脑或手机，解压后，使用本地浏览器打开 `index.html`，不需要联网也可以随时使用。在 Windows、Mac、Android 的 Chrome、Firefox 浏览器下，均可以工作，iphone 还没测试。

本项目鼓励大家自由地部署和分发，在墙内以更隐蔽的方式使用。但需要注意，如果使用的不是官网或直接从官网获取的压缩包，请确保工具是由你所信任的人部署或提供，以防程序被人更改，窃取信息。

## Dependencies

此项目基于 html 和 JavaScript，在 [NajmAjmal/PGP](https://github.com/NajmAjmal/PGP) 的基础上汉化，在界面布局上略作修改。涉及到的 JavaScript 开源项目包括：

- [kbpgp.js](https://github.com/keybase/kbpgp)
- jQuery
- [FileSaver.js](https://github.com/eligrey/FileSaver.js)
- Bootstrap

## License

延用了[原项目](https://github.com/NajmAjmal/PGP)的 Apache License 2.0 协议。
