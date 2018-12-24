
### 使用说明
点击 `开始录音` 即可开始说话

点击 `结束录音` 即开始识别语音

可以尝试着说 **“我要去” + 下面任何一个地点**，如果所说地点不在以下列表内将无法触发相应功能。匹配关键词 **“去”+地点**，所以你也可以说 “我想去xx”、“带我去xx”....
```js
var geoCood = [
    {name:'兰州', geoCoord:[103.73, 36.03]},
    {name:'西宁', geoCoord:[101.74, 36.56]},
    {name:'成都', geoCoord:[104.06, 30.67]},
    {name:'石家庄', geoCoord:[114.48, 38.03]},
    {name:'昆明', geoCoord:[102.73, 25.04]},
    {name:'贵阳', geoCoord:[106.71, 26.57]},
    {name:'武汉', geoCoord:[114.31, 30.52]},
    {name:'郑州', geoCoord:[113.65, 34.76]},
    {name:'济南', geoCoord:[117, 36.65]},
    {name:'南京', geoCoord:[118.78, 32.04]},
    {name:'合肥', geoCoord:[117.27, 31.86]},
    {name:'杭州', geoCoord:[120.19, 30.26]},
    {name:'南昌', geoCoord:[115.89, 28.68]},
    {name:'福州', geoCoord:[119.3, 26.08]},
    {name:'广州', geoCoord:[113.23, 23.16]},
    {name:'长沙', geoCoord:[113, 28.21]},
    {name:'海口', geoCoord:[110.35, 20.02]},
    {name:'沈阳', geoCoord:[123.38, 41.8]},
    {name:'长春', geoCoord:[125.35, 43.88]},
    {name:'哈尔滨', geoCoord:[126.63, 45.75]},
    {name:'太原', geoCoord:[112.53, 37.87]},
    {name:'西安', geoCoord:[108.95, 34.27]},
    {name:'台湾', geoCoord:[121.30, 25.03]},
    {name:'北京', geoCoord:[116.46, 39.92]},
    {name:'上海', geoCoord:[121.48, 31.22]},
    {name:'重庆', geoCoord:[106.54, 29.59]},
    {name:'天津', geoCoord:[117.2, 39.13]},
    {name:'呼和浩特', geoCoord:[111.65, 40.82]},
    {name:'广西', geoCoord:[108.33, 22.84]},
    {name:'拉萨', geoCoord:[91.11, 29.97]},
    {name:'银川', geoCoord:[106.27, 38.47]},
    {name:'新疆', geoCoord:[87.68, 43.77]},
    {name:'香港', geoCoord:[114.17, 22.28]},
    {name:'澳门', geoCoord:[113.54, 22.19]}
]
```

### 兼容性
兼容 Chrome 和火狐，不支持IE浏览器