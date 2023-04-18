[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey.svg)][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/wx-chevalier/InfoSecurity-Series">
    <img src="https://s2.ax1x.com/2020/02/02/1YM1JK.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">InfoSecurity & PenTest</h3>

  <p align="center">
    信息安全与渗透测试
    <br />
    <a href="https://github.com/wx-chevalier/InfoSecurity-Series"><strong>在线阅读 >> </strong></a>
    <br />
    <br />
    <a href="https://github.com/wx-chevalier/InfoSecurity-Series">速览手册</a>
    ·
    <a href="https://github.com/wx-chevalier/InfoSecurity-Series/issues">InfoSecurity-Seriesrt Bug</a>
    ·
    <a href="https://github.com/wx-chevalier/InfoSecurity-Series/issues">参考资料</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->

# Introduction | 前言

安全是当今 IT 相关头条新闻的一个重要话题。经常出现的系统漏洞和安全补丁以及病毒和蠕虫是每个使用计算机的人都耳熟能详的名词。因为几乎每台计算机系统都连接到另外的计算机或者连接到 Internet，因此确保这些计算机的安全，对于减少入侵、数据窃取或丢失、误用甚至对第三方的责任而言是至关重要的。确保安全即使对于没有连接到网络的独立的计算机也是很重要的。必须自可信赖的来源安装应用程序，比如 经过验证的并检查过病毒的光盘。对应用程序数据也必须同样小心。例如，对于可以执行强大的宏语言 或者引入非法数据的软件程序包(office 套件等等)，其软件缺陷可能会被利用来执行任意的代码。因此，应用程序数据在拷贝到计算机之前必须经过完整性检查。可以通过将数据放置在一个安全的地方来控制对 系统的访问(当然，不考虑来自已授权人员的攻击)。

当系统连接到网络并向其他计算机提供服务(有意地或无意地)时，事情会变得更为棘手。在那种情况下，数据可能不只是来自系统管理员，因为客户机程序要使用所提供的服务，而系统漏洞可能会让入侵者控制 计算机。这就是为什么安全是从开始计划直到拆除系统的整个系统生命周期中最基本的问题。

![mindmap](https://assets.ng-tech.icu/item/20230418154054.png)

> 本书的精排目录导航版请参考 [https://ng-tech.icu/books/InfoSecurity-Series](https://ng-tech.icu/books/InfoSecurity-Series)。

## 数据安全与系统安全

从宏观层面上，安全可以被分为系统安全与数据安全两个层面。数据安全和系统安全可以分开来考虑。数据安全通常被认为是确保以下方面的所有努力：

- 机密性(Confidentiality )。
- 完整性(Integrity )。
- 可用性(Availability )。

综合起来，这些被称作是存储在计算机上的数据的 CIA。对 `/etc/passwd` 等配置数据的保护可以归类为数据安全。

系统安全指的是计算机平台本身。美国 NationalInformation Systems Security Glossary 以获得链接)对系统安全的定义如下：对信息系统的保护，防止未授权的访问及对信息(不论是存储中的、正在处理的还是正在传输的)的修改，并防止对授权用户服务的拒绝或对未授权用户服务的允许，包括那些检测、记录和反击此类威胁的措施。重要的是要认识到系统安全强调的是一个反复的过程，这个过程包括应用安全补丁、经常审计、控制，同时最起码要有一个安全的系统配置。就此而言，不可能保证绝对的安全，也不可能提供百分之百安全的服务。目标更应该是在安全性、系统可用性和维护这个安全层级所需要的努力这三者之间找到一个折衷点。这个折衷取决于安全对于存储在计算机中的数据来说的重要性以及这些数据预期的使用情形。

# Nav | 关联导航

# About | 关于

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Awesome-Lists](https://github.com/wx-chevalier/Awesome-Lists): 📚 Guide to Galaxy, curated, worthy and up-to-date links/reading list for ITCS-Coding/Algorithm/SoftwareArchitecture/AI. 💫 ITCS-编程/算法/软件架构/人工智能等领域的文章/书籍/资料/项目链接精选。

- [Awesome-CS-Books](https://github.com/wx-chevalier/Awesome-CS-Books): :books: Awesome CS Books/Series(.pdf by git lfs) Warehouse for Geeks, ProgrammingLanguage, SoftwareEngineering, Web, AI, ServerSideApplication, Infrastructure, FE etc. :dizzy: 优秀计算机科学与技术领域相关的书籍归档。

## Copyright & More | 延伸阅读

笔者所有文章遵循[知识共享 署名 - 非商业性使用 - 禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。您还可以前往 [NGTE Books](https://ng-tech.icu/books-gallery/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

[![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)](https://ng-tech.icu/books-gallery/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/wx-chevalier/InfoSecurity-Series.svg?style=flat-square
[contributors-url]: https://github.com/wx-chevalier/InfoSecurity-Series/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/wx-chevalier/InfoSecurity-Series.svg?style=flat-square
[forks-url]: https://github.com/wx-chevalier/InfoSecurity-Series/network/members
[stars-shield]: https://img.shields.io/github/stars/wx-chevalier/InfoSecurity-Series.svg?style=flat-square
[stars-url]: https://github.com/wx-chevalier/InfoSecurity-Series/stargazers
[issues-shield]: https://img.shields.io/github/issues/wx-chevalier/InfoSecurity-Series.svg?style=flat-square
[issues-url]: https://github.com/wx-chevalier/InfoSecurity-Series/issues
[license-shield]: https://img.shields.io/github/license/wx-chevalier/InfoSecurity-Series.svg?style=flat-square
[license-url]: https://github.com/wx-chevalier/InfoSecurity-Series/blob/master/LICENSE.txt
