# My scoop bucket
> Some interesting and useful apps available for windows platform

## Usage (under testing)

1. Install [scoop](https://scoop.sh/) first
2. In powershell or cmd: `scoop bucket add scoop-it https://github.com/younger-1/scoop-it`

## Todo

<https://github.com/nabijaczleweli/termimage>

<https://github.com/ahrm/sioyek>


## Auto update

<https://github.com/chawyehsu/dorado/issues/28>

```ps1
# See the available paras
vim ('{0}/bin/checkver.ps1' -f (scoop prefix scoop))

# `-forceupdate` is useful for hash
.\bin\checkver.ps1 -forceupdate
```
