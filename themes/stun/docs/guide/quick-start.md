# Quick start

## Installation

- Install `stun`

  Enter your hexo directory, run this.

  ``` bash
  $ git clone https://github.com/liuyib/hexo-theme-stun.git themes/stun
  ```

- Install dependency `pug`

  Enter your hexo directory, run this.

  ``` bash
  $ npm install --save hexo-render-pug
  ```

## How to use

Change the `_config.yml` file in your hexo root directory.

``` yml
theme: stun
```

Run your hexo server.

``` bash
$ hexo clean && hexo s
```

## Update

``` bash
$ cd themes/stun

# Update to stable version (recommend).
$ git pull origin master

# Update to the latest features (May be unstable and not recommended).
$ git pull origin dev
```
