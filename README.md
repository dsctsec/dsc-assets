# DSC TSEC Assets

**Assets, images and content for DSC TSEC.**

<!-- ![](GDSC_Thadomal_Shahani_Engineering_College_vertical_color.png) -->
![](DSC_TSEC_Banner.png)

</br>
</br>

Script used for renaming the files.

```bash
for file in *; do mv "$file" `echo $file | tr ' ' '_'`; done
```
