# atsa-es.r-universe.dev

https://atsa-es.r-universe.dev/packages: CRAN-like repository for the atsa-es packages. Binaries are available for Windows and MacOS (not M1 however).

To install packages from the ATSA-ES Repository:

```
options(repos = c(
    atsa = 'https://atsa-es.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))
```

Then you can install any of our packages. If you are on Linux, Windows, or macos-Intel, then you should not have to build from source. After running the code above to add our repo to the options, install as

```
install.packages('pkgname')
```

or you can run
```
install.packages('pkgname', repos = c(atsa = 'https://atsa-es.r-universe.dev', CRAN = 'https://cloud.r-project.org'))
```

https://r-universe.dev/welcome/?installation_id=36737048&setup_action=install

https://ropensci.org/blog/2021/06/22/setup-runiverse/
