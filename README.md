<h1 align="center">
  <br>
  <img src="https://github.com/Safe3/openresty-manager/blob/main/logo.png" alt="OpenResty Manager" width="70px">
</h1>
<h4 align="center">OpenResty Manager</h4>

<p align="center">
<a href="https://github.com/Safe3/openresty-manager/releases"><img src="https://img.shields.io/github/downloads/Safe3/openresty-manager/total">
<a href="https://github.com/Safe3/openresty-manager/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/Safe3/openresty-manager">
<a href="https://github.com/Safe3/openresty-manager/releases/"><img src="https://img.shields.io/github/release/Safe3/openresty-manager">
<a href="https://github.com/Safe3/openresty-manager/issues"><img src="https://img.shields.io/github/issues-raw/Safe3/openresty-manager">
<a href="https://github.com/Safe3/openresty-manager/discussions"><img src="https://img.shields.io/github/discussions/Safe3/openresty-manager">
</p>
<p align="center">
  <a href="#dart-features">Features</a> •
  <a href="#rocket-usage">Usage</a> •
  <a href="#gift_heart-credits">Credits</a> •
  <a href="#kissing_heart-contact">Contact</a> •
  <a href="#key-license">License</a>
</p>






<p align="center">
  <a href="https://github.com/Safe3/openresty-manager/blob/main/README_CN.md">中文</a>
  <br/><br/>
  ⭐Please help us with a star to support our continuous improvement, thank you!
</p>




---

Modern, secure, and elegant server control panel, open source alternative to OpenResty Edge, allows you to easily secure reverse proxy websites running at home or on the Internet, including access control, denial of service attack protection, identity authentication, automatic application and renewal of free SSL certificates, without having to know too much about OpenResty or Let's Encrypt. And it supports host management, including easy-to-use web terminals and file management, as well as Docker Composer based application store, greatly reducing the difficulty of website building and container management.

<h3 align="center">
  <img src="https://github.com/Safe3/openresty-manager/blob/main/docs/openresty-manager.png" alt="Dashboard" width="700px">
  <br>
</h3>

<h3 align="center">
  <img src="https://github.com/Safe3/openresty-manager/blob/main/docs/appstore.png" alt="Appstore" width="700px">
  <br>
</h3>


## :dart: Features
:green_circle: ‌The simplest OpenResty management product accessible via web interface.

:purple_circle: Supports comprehensive security capabilities including access control, HTTP Flood protection, and identity authentication.

:yellow_circle: Enables multiple free certificate application protocols with automatic renewal hosting.

:red_circle: Features host management with web-based command terminal and file management.

:large_blue_circle: Includes app marketplace and container management, making website construction simpler than ever before.

:orange_circle: Offers multi-node management for batch administration of multiple servers.

:brown_circle: Delivers distributed CDN caching acceleration for building CDN clusters.



## :rocket: Usage

OpenResty Manager is not only easy to use but also easy to install, supports both host and container environments.

- ### Host Version

> :biohazard: ***If the server is using cloud services, remember to open the TCP port 80, 443 and 34567 required for OpenResty Manager***

One click installation: Automatic installation can be completed in minutes.


> [!WARNING]
> 中国用户请访问 [中文官网](https://om.uusec.com/cn/) 安装中文版，以下步骤安装国际版可能会导致无法使用！

```bash
sudo bash -c "$(curl -fsSL https://om.uusec.com/installer.sh)"
```

- ### Docker Version

One click installation: Automatic installation can be completed in minutes.


> [!WARNING]
> 中国用户请访问 [中文官网](https://om.uusec.com/cn/) 安装中文版，以下步骤安装国际版可能会导致无法使用！

```bash
sudo bash -c "$(curl -fsSL https://om.uusec.com/docker_installer.sh)"
```

Subsequently, `bash /opt/om/om.sh` is used to manage the OpenResty Manager container, including starting, stopping, updating, uninstalling, etc.

- ### Quick Start

1. Login to the management: Access https://your-ip:34567 , the default username is "admin", and the default password is "#Passw0rd".
2. Add SSL certificates: Go to the certificates management menu, apply for a Let's Encrypt free SSL certificate or upload an existing certificate.
3. Add apps: Go to the app store menu and install apps such as WordPress with just one click.
4. Add upstreams: Go to the upstream management menu and add upstream load balancing for installed applications such as WordPress.
5. Add a site: Go to the sites menu, click the "New site" button, and follow the prompts to add the site domain names for reverse proxy.
6. Test connectivity: Change your domain dns A or CNAME record to the OpenResty Manager server IP, visit your website to see if it can be opened.

- ### Uninstall

One click uninstallation: Automatic uninstallation can be completed in minutes.

```bash
sudo bash -c "$(curl -fsSL https://om.uusec.com/uninstaller.sh)"
```


## :1st_place_medal: Product List

Other great products from us:

[UUSEC WAF](https://github.com/Safe3/uusec-waf) - AI and semantic technology Web Application Firewall and API Security Gateway (WAAP).



## :gift_heart: Credits

Thanks to all the amazing [community contributors for sending PRs](https://github.com/Safe3/openresty-manager/graphs/contributors) and keeping this project updated. ❤️

If you have an idea or some kind of improvement, you are welcome to contribute and participate in the Project, feel free to send your PR.

<p align="center">
<a href="https://github.com/Safe3/openresty-manager/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Safe3/openresty-manager&max=500">
</a>
</p>
<a href="https://auraplusplus.com/projects/openresty-manager" target="_blank" title="Aura++ Top 1 Daily Winner">
  <img 
    src="https://auraplusplus.com/images/badges/top1-light.svg" 
    alt="Aura++ Top 1 Daily Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

## :kissing_heart: Contact

If you want to support more features , please send mail to support[at]uusec.com .


## :key: License

OpenResty Manager is under GPL license, everyone can use it for free！

