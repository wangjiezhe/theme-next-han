<h1 align="center"><a href="https://hanzi.pro">Han</a> for <a href="https://github.com/theme-next">NexT</a></h1>

<h2 align="center">Installation</h2>

**1.** Change dir to **NexT** directory. There must be `layout`, `source`, `languages` and other directories:

```sh
$ cd hexo/themes/next
$ ls
bower.json  _config.yml  docs  gulpfile.coffee  languages  layout  LICENSE.md  package.json  README.md  scripts  source  test
```

**2.** Install module to `source/lib` directory:

```sh
$ git clone https://github.com/theme-next/theme-next-han source/lib/Han
```

**3.** Enable module in **NexT** `_config.yml` file:

```yml
# Han Support docs: https://hanzi.pro/
han: true
```

<h2 align="center">Update</h2>

```sh
$ cd themes/next/source/lib/Han
$ git pull
```
