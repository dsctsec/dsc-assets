# DSC TSEC Assets

Assets, images and content for DSC TSEC.

![](DSC_Thadomal_Shahani_Engineering_College_Light_Vertical-Logo.png)

Script used for renaming the files.

```bash
for file in *; do mv "$file" `echo $file | tr ' ' '_'`; done
```