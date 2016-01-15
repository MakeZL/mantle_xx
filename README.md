# mantle_xx

#### 因Mantle升级到2.0.5,没有对接口的属性进行兼容, 如果你也是基于此, 可以覆盖`MTLJSONAdapter.m` `NSValueTransformer+MTLPredefinedTransformerAdditions.h`,`NSValueTransformer+MTLPredefinedTransformerAdditions.m`两个文件兼容了mantle在属性转换出错的兼容, debug提示出错的文件与类型, 非debug会兼容int与string
