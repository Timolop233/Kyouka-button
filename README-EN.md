![1624762654518](./kyouka.jpg)

##### atr:[結月とば_](https://space.bilibili.com/8799104)

# 京华破防站[Kyouka-Button]🔨

[EN/[中文](https://github.com/Timolop233/Kyouka-button/blob/main/README.md)/[日本语](https://github.com/Timolop233/Kyouka-button/blob/main/README-JA.md)]

------

We have a function that all button stations don't have, and that's--------

#### **Let Kyouka shut down**

------

### Contribute to the project
 Use git to make a fork to the project

 Commit to your fork's *main* branch and make a pull request to this repository

 Files need to be changed:
 
[Add Voices]：`setting\translate\01_voices.json`
 
[Add new categories]：`setting\translate\category.json`

[Path for voices]：`public\voices`

[Path for images]：`public\voices\img`

<br/>

​	an example for `01_voices.json`:

```json
{
    "name": "赢了", //You may se voice's name, but no duplicates!! 
    "path": "赢了.mp3", //name for the voices, use audio name from public\voices (remember to use mp3 format)
    "date": "2020-02-15", //Update date of the voice
    "translate": { //
      "zh-CN": "赢了，赢了，赢了！！！", //Name of the button in Chinese
      "en-US": "Kyouka Bible" //Same as above, but in English
    },
    "usePicture": { 
      "zh-CN": "", //Name of the sticher in public\voices\img 
      "en-US": ""  //Same as above
    },
    "category": "圣经", //This string binds with 'name' in category.json
    "mark": { //'title' for the title of video source, 'time' for its timestamp, 'url' for its url
      "title": "【哭了】张京华被绿了？谁是泠鸢呢？【完全胜利ED】",
      "time": "",
      "url": "https://www.bilibili.com/video/BV1z7411J7c2"
    }
}
```

an example for `category.json`:

```json
{
    "name": "圣经", //Category name, musn't be duplicated
    "translate": {
      "zh-CN": "京 典 名 场 面",  //Chinese category name displayed on the site
      "en-US": "Kyouka famous scene"   //English category name
    }
```

If you dunno how to use GitHub，you can use this [Issue](https://github.com/YYRDIO/Kyouka-button/issues/17) to submit voices you know, we'll add it.

------

### **LICENSE** ###

\- Used [voices-button-cli](https://github.com/blacktunes/voices-button-cli) to create the button site.

\- Template from [Hiiro button](https://github.com/blacktunes/hiiro-button)


------