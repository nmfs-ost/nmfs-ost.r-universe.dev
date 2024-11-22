# nmfs-ost.r-universe.dev

https://nmfs-ost.r-universe.dev/packages: CRAN-like repository for the nmfs-ost packages. Binaries are available for Windows and MacOS (not M1 however).

To install packages from the nmfs-ost Repository:

```
options(repos = c(
    nmfs-ost = 'https://nmfs-ost.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))
```

Then you can install any of our packages. If you are on Linux, Windows, or macos-Intel, then you should not have to build from source. After running the code above to add our repo to the options, install as

```
install.packages('pkgname')
```

or you can run
```
install.packages('pkgname', repos = c(nmfs-ost = 'https://nmfs-ost.r-universe.dev', CRAN = 'https://cloud.r-project.org'))
```

https://r-universe.dev/welcome/?installation_id=36737048&setup_action=install

https://ropensci.org/blog/2021/06/22/setup-runiverse/

## Disclaimer

“The United States Department of Commerce (DOC) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. DOC has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce stemming from the use of its GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.”
