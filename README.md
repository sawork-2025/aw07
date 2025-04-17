# aw07 - Big data for MicroPos


[Amazon Review Data (2023)](https://amazon-reviews-2023.github.io/) 是一个包含从1996年到2023年间Amazon商品、用户和评价数据的海量数据集，概况如下：

|评论| 用户 | 商品 |
|--| -- | -- |
|571.54M|54.51M|48.19M|


请完成以下任务

- 下载至少两大类商品的元数据(metadata)和评论数据(reviews)；
  - 在云盘中提供了已下载的部分数据（https://box.nju.edu.cn/d/3e125ec5ca2f476db822/)
- 请使用spring batch将原始格式的数据分别转为User/Product/Review三类对象，包括其间关联关系，并将数据保存到数据库；
  - 请额外考虑一些复杂的处理，比如将英文翻译为中文、测试图片url是否有效等；
- 请将数据库整合进你的MicroPOS（微服务版本的POS系统）并对系统进行相应改造，要求系统使用者可以通过浏览器中的web前端看到商品列表、点击商品后可以看到商品详情和商品相关的评论列表；
- 编写README.md，着重介绍你做了那些处理步骤以及如何使得数据转化处理过程尽量快速。
