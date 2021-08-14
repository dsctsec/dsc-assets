# DSC TSEC Assets

**Assets, images and content for DSC TSEC.**

![](DSC_TSEC_Banner.png)

</br>
</br>

Script used for renaming the files.

```bash
for file in *; do mv "$file" `echo $file | tr ' ' '_'`; done
```

## References

A huge thank you to:

- [dscnsec/logo-generator](https://github.com/dscnsec/logo-generator)
- [mbaraa/dsc_logo_generator](https://github.com/mbaraa/dsc_logo_generator)
- [abhinavsri360/GDSC-Lead-Map](https://github.com/abhinavsri360/GDSC-Lead-Map)
