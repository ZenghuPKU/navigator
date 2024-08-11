### Login
Please see instructions in the [SSH&DataManagement.md](https://github.com/ZenghuPKU/zenglab_server/blob/main/SSH%26DataManagement.md) page

### Copy script to your own space.
**You only need to copy this once; later, you can just use it in your own directory.**
```batchfile
cp /media/zenglab/script/yly/navigator.R /media/zenglab/result/YourDirectory/navigator.R
```

### Open RStudio Server in your browser

http://10.128.243.62:8787

1. Switch path /media/zenglab/result/YourDirectory in the right panel
2. Click navigator.R
3. Click "Source" button to run all the code.
4. Follow the instructions to sequentially input the path, rgn file name, and maf file name. An output maf file and a plot.png file are expected to be generated.

Here is an example. Ignore any warnings. When the > prompt appears again, it means the operation has finished.

```batch
> source("/media/zenglab/result/lingyuan2/leica/navigator.R")
Please enter the working directory path: /media/zenglab/result/lingyuan2/leica
Please enter the .rgn filename: A2A3A5.rgn
Please enter the .maf filename: A2A3A5.maf
Warning message:
In readLines(rgn_filename) : incomplete final line found on 'A2A3A5.rgn'
> 
```
