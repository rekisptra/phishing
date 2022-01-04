### Features

- Latest and updated login pages.
- Mask URL support 
- Beginners friendly
- Docker support (checkout `docker-legacy` branch)
- Multiple tunneling options
  - Localhost
  - Ngrok (With or without hotspot)
  - Cloudflared (Alternative of Ngrok)


### Installation
 
* `apt update`
* `apt install git curl php openssh-server -y`
* `git clone git://github.com/RekiXploit/phising`
* `cd ZPhisher`
#### > Run : `bash phishing.sh`

## Single Command :
```
apt update ; apt install git curl php openssh-server -y ; git clone git://github.com/RekiXploit/phishing ; cd phishing ; bash phishing.sh
```
- On first launch, It'll install the dependencies and that's it. `phishing` is installed.

### Run on Docker
```
$ docker pull htrtech/phishing
$ docker run --rm -it htrtech/phishing
```

### Dependencies

**`phishing`** requires following programs to run properly - 
- `php`
- `wget`
- `curl`
- `git`

> All the dependencies will be installed automatically when you run `phishing` for the first time.

> Supported Platform : **`Termux`**, **`Ubuntu/Debian/Kali/Parrot`**, **`Arch Linux/Manjaro`**, **`Fedora`**

