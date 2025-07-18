 - 包含2025年全国各省市高考真题，覆盖9个学科，统一按学科来归类数据，比如语文json文件会包含全国所有开放的真题，具体来自哪个省市会标记在`detail`字段。
 - 为方便评测，我们只保留纯文本的客观题，对于带图的题目，我们留给以后“多模态评测”版块。
 - 当前版本，各学科的题数分别为：语文28题，数学108题，英语33题，物理59题，化学41题，生物80题，历史68题，地理19题，政治77题。

样本举例：
```
  {
    "prompt": "牡蛎、贻贝等双壳贝类环境适应性强，主要滤食浮游生物和有机颗粒，其生长过程中吸收并固定二氧化碳。福建省莆田市秀屿区是重要的双壳贝类养殖基地。近年来，莆田市持续开展海上养殖转型升级，引导海上养殖向生态化方向发展。2022年5月，福州市某企业出资20余万元，向秀屿区某水产养殖公司购买双壳贝类碳汇，用于抵消其生产经营活动中的碳排放，是全国首例双壳贝类碳汇交易。根据材料完成下面小题。\n\n扩大秀屿区牡蛎养殖碳汇量的有效措施是（ ）\n（A） 增加养殖品种\n（B） 降低企业碳排放\n（C） 改善养殖水质\n（D） 提升养殖单产水平\n",
    "reference": "D",
    "class": "2025高考地理",
    "id": "ReLE-5e9151632",
    "detail": "2025年辽宁、黑龙江、吉林、内蒙古普通高校选择性考试-地理-选择题-5"
  }
```

字段说明：
 - prompt：题目
 - reference：参考答案
 - class：学科类别
 - id：prompt唯一标识
 - detail：补充信息，比如真题来自哪个省市
