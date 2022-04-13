![1624762654518](./index.jpg)
##### art:边阳[[bilibili](https://space.bilibili.com/3189128)]

# 京华破防站[Kyouka-Button]🔨

我们拥有所有按钮站都没有的功能，那就是--------

#### **让主播破防**

------

### 本项目于2021年4月重启！

------

### 项目参与

​	通过fork项目使用git克隆项目

​	提交分支main

​	你需要更改的文件如下

​	[语言文件路径]：`setting\translate\01_voices.json`

​	[Tag列表]：`setting\translate\category.json`

​	[音频存放路径]：`public\voices`

​	[图片存放路径]：`public\voices\img`

<br/>

  本项目更推荐使用yarn脚本测试部署！

  在保证你的环境中有node<=16.00.00版本 npm<=8.5.0后
  
  [查看node和npm版本代码为`node -v`和`npm -v`]

  输入`npm install yarn -g`即可安装yarn
  
  或者通过[yarn官网](https://yarn.bootcss.com/)安装yarn

  在你更改完代码后，输入`yarn && yarn serve`即可查看效果


<br/>

​	`01_voices.json`解析如下

```json
{
    "name": "赢了", /*按钮tag（也可以说是按钮名字，请保持唯一），*/
    "path": "赢了.mp3", //这里为音频文件名称，直接填写public\voices的音频文件即可(注意，是mp3格式哦)
    "date": "2020-02-15", //填写按钮更新日期即可
    "translate": { //按钮名字
      "zh-CN": "赢了，赢了，赢了！！！", //按钮在中文状态下显示的名字
      "en-US": "Kyouka Bible" //按钮在英语状态下显示的名字
    },
    "usePicture": { //按钮表情
      "zh-CN": "", //这里是中文界面按钮表情包的文件名称，填写public\voices\img的图片名称即可
      "en-US": ""  //这里是英文界面按钮表情包的文件名称，填写public\voices\img的图片名称即可
    },
    "category": "圣经", //该字段绑定category.json列表的name（也可以说是tag）字段
    "mark": { //下面的三个分别填写视频名称'title'、所处时间段'time'、出处视频链接'url'
      "title": "【哭了】张京华被绿了？谁是泠鸢呢？【完全胜利ED】",
      "time": "",
      "url": "https://www.bilibili.com/video/BV1z7411J7c2"
    }
}
```

`category.json解析如下`

```json
{
    "name": "圣经", //Tag名，保持唯一值（说人话就是不能有重复）
    "translate": {
      "zh-CN": "京 典 名 场 面",  //中文状态下的列表名称
      "en-US": "Kyouka famous scene"   //英语状态下的列表名称
    }
```

当然，如果你不会可以通过[这里](https://github.com/Timolop233/Kyouka-button/issues/17)提交你知道的怪话，我们会更新的。

------

### LICENSE
- 使用[voices-button-cli](https://github.com/blacktunes/voices-button-cli)创建的语音按钮
- 所用模板为[Hiiro按钮](https://github.com/blacktunes/hiiro-button)