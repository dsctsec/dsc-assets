# DSC TSEC Assets

**Assets, images and content for DSC TSEC.**

<br>

<p align="center"><img width="20%" src = "gdsc-logo-animation.gif" styles></p>
<p align="center"><img width ="45%" src="DSC_LOGOS/gdsc.png"></p>

<br><br>

Script used for renaming the files.

```bash
for file in *; do mv "$file" `echo $file | tr ' ' '_'`; done
```

## References

A huge thank you to ❤

- [dscnsec/logo-generator](https://github.com/dscnsec/logo-generator)
- [mbaraa/dsc_logo_generator](https://github.com/mbaraa/dsc_logo_generator)
- [abhinavsri360/GDSC-Lead-Map](https://github.com/abhinavsri360/GDSC-Lead-Map)
