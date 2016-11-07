````shell
ls -al . | awk '{print $9}' | echo $(basename $(cat -)) | tr -d '\n' | pbcopy
```
