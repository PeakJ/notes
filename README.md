# notes
## markdown语法片段
> 这个readme文档仅仅是为了联系记录一些markdown的用法
内容随意为之，没有任何实际意义，可以忽略>引用中的引用
[百度](https://www.baidu.com)

**加粗字体**
*倾斜字体*
<div>这段文字放在了一个div标签中</div>
<span>这段文字放在了一个**span**标签中了</span>

***
上面是分割线

###列表
####无序
- 第一项
- 第二项
- 第三项
###有序
1. 第四项
2. 第五项
第五项增加内容
3. 第六项
2. 第七项

###代码片段
` var obj = eval(response.data);
  $scope.provinceId = obj[0].provinceId;
  $scope.cityId = obj[0].cityId;
  $scope.regionId = obj[0].areaId;
  $scope.streetId = obj[0].streetId;
  var regionIndex = obj[0].regionName.indexOf('/');
  $scope.region = obj[0].regionName.substr(0, regionIndex);
  $scope.findInit();
  `
    区块区块区块区块
    区块区块区块区块
    区块区块区块区块
---------------------------------------------
![测试图片](https://ss0.bdstatic.com/94oJfD_bAAcT8t7mm9GUKT-xh_/timg?image&quality=100&size=b4000_4000&sec=1478072465&di=709e8ec35ddfbbaff7997f038fd9e403&src=http://img.hb.aicdn.com/761f1bce319b745e663fed957606b4b5d167b9bff70a-nfBc9N_fw580)
