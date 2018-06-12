这里分享一些实用脚本

## 合并视频

First create a file called inputs.txt which looks like this:

```
file 'input1.flv'
file 'input2.flv'
```

Then use ffmpeg like so:

```
ffmpeg -f concat -i inputs.txt -c copy output.mp4
```

[How to concatenate two flv files?](https://superuser.com/questions/420363/how-to-concatenate-two-flv-files)
