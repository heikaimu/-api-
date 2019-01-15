## base url
https://api.douban.com/v2

## 电影

===== 列表 type=in_theaters/coming_soon/top250
/movie/${type}?start=0&count=20

### 详情 movieId
/movie/subject/${movieId}

## 演员 actorId
/movie/celebrity/${actorId}

## 图书

### 标签
tags: [{"title":"文学","tag":["小说","外国文学","文学","随笔","中国文学","经典","日本文学","散文","村上春树","诗歌","童话","王小波","杂文","古典文学","儿童文学","名著","张爱玲","余华","当代文学","钱钟书","外国名著","鲁迅","诗词","茨威格","米兰·昆德拉","杜拉斯","港台"]},{"title":"流行 ","tag":["漫画","绘本","推理","青春","东野圭吾","科幻","言情","悬疑","武侠","奇幻","韩寒","日本漫画","耽美","亦舒","推理小说","三毛","网络小说","安妮宝贝","郭敬明","穿越","金庸","轻小说","阿加莎·克里斯蒂","几米","科幻小说","魔幻","青春文学","张小娴","幾米","J.K.罗琳","高木直子","古龙","沧月","落落","张悦然","校园"]},{"title":"文化","tag":["历史","心理学","哲学","传记","文化","社会学","艺术","设计","社会","政治","建筑","宗教","电影","数学","政治学","回忆录","中国历史","思想","国学","音乐","人文","人物传记","绘画","戏剧","艺术史","佛教","军事","西方哲学","二战","近代史","考古","自由主义","美术"]},{"title":"生活","tag":["爱情","旅行","生活","成长","励志","心理","摄影","女性","职场","美食","教育","游记","灵修","健康","情感","手工","两性","养生","人际关系","家居","自助游"]},{"title":"经管","tag":["经济学","管理","经济","商业","金融","投资","营销","创业","理财","广告","股票","企业史","策划"]},{"title":"科技","tag":["科普","互联网","编程","科学","交互设计","用户体验","算法","web","科技","UE","通信","交互","UCD","神经网络","程序"]}]
    
### 列表 
/book/search?tag=${tag}&start=0&count=20&fields=id,title,images

### 详情
/book/${bookId}
