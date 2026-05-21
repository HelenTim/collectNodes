# collectNodes
搜集翻墙节点

## 配置文件一：
   - 文件：daily-source.list，用于收集订阅链接是按照日期格式生成的。后面添加了日和月是否需要零补齐的配置以及文件后缀
   - // https://sfdr.zaixianyouxi.dpdns.org/uploads 1 1   → 月补零、日补零（05/21）
   - // https://another.com/path 0 0                   → 月不补零、日不补零（5/21）
   - ```
      # 格式：链接 月补零 日补零 后缀
      https://sfdr.zaixianyouxi.dpdns.org/uploads 1 1 .yaml
      https://sfdr.zaixianyouxi.dpdns.org/data 0 0 .txt
      https://api.abc.com/node 1 0 ?auth=123
      https://test.xyz.com/path 0 1
      // 生成结果
      https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/05/20260521.yaml
      https://sfdr.zaixianyouxi.dpdns.org/data/2026/5/20260521.txt
      https://api.abc.com/node/2026/05/20260521?auth=123
      https://test.xyz.com/path/2026/1/20260521
     ```
    
