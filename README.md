## What is this project? ![](https://img.shields.io/badge/license-MIT-green)

If you have a domain [https://www.tailieubkhn.com/2021/10/website-hoc-machine.html](https://www.tailieubkhn.com/2021/10/website-hoc-machine.html), so you want share it to facebook or twitter, that you want avoid facebook or twitter block your domain, this is solution you need. This project help convert your domain to github domain, Because it is the domain of github, it has a certain reputation

## Demo: 

[https://piandhust.github.io/tailieubkhn/convert](https://piandhust.github.io/tailieubkhn/convert), and paste domain you want convert from website tailieubkhn to github pages, domain [https://www.tailieubkhn.com/123](https://www.tailieubkhn.com/2021/10/website-hoc-machine.html) will convert to [https://piandhust.github.io/tailieubkhn/123](https://piandhust.github.io/tailieubkhn/2021/10/website-hoc-machine.html), And when you access to link github page you will see a website have a button _Continue_, click to button _Continue_ website will redirect to [https://www.tailieubkhn.com/](https://www.tailieubkhn.com/):

| ![](https://raw.githubusercontent.com/piandhust/tailieubkhn/master/images/convert.png) |
| :----: |
| Convert website |

| ![](https://raw.githubusercontent.com/piandhust/tailieubkhn/master/images/home.png) |
| :----: |
| Website redirect |


## Configuration

Edit file `_config.yml`: 
```yml
permalink: /404.html
url: "piandhust.github.io"
targeturl: "tailieubkhn.com"
baseurl: "tailieubkhn"
```

With: 
- `url` is url of your github page website, if your username is trannguyenhan, this is trannguyenhan.github.io
- `targeturl` is url of target website you want convert domain from github page to it
- `baseurl` is name of this repo

**Note**: because domain `/convert` has been taken to make a website to convert, so your domain will ignore `/convert`.
