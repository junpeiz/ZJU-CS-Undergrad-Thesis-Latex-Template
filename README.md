# ZJU CS Undergraduate Thesis LaTeX Template

By Junpei Zhou



### Notice

1. It is modified based on template provided by Hai Zhang
2. Updated to the new style requirements in 2018 (but not sure if it can be used for 2019 and later)
3. 主要还是用`thesis`的template，`proposal`里的貌似不是我用的最新版，连cite都是hardcode进去的。
4. 在Mac上可能会有`中易宋体`和`中易黑体`无法安装的问题，可以自行选择其他类似的宋体或者黑体（已经有学弟编译成功了，所以应该是reliable的）
5. As it is accomplished a year ago, I cannot remember the exact details. If fail to run, please figure out it on your own. 

Thanks.



### Structure

- `proposal` folder contains the tex file for 开题报告
- `thesis` folder contains the tex file for 最终的毕业论文

According to the requirements from department, you should first generate the `文献综述和开题报告` from `proposal`, and then you can use the `thesis` folder, as you can see there is `\includepdf[pages=-]{kaitibaogao.pdf}` in `main.tex`.