# collectNodes
搜集翻墙节点

## 配置文件一：
   - 文件：daily-source.list，用于生成订阅链接是按照日期格式生成的链接。
   - ```
      https://sfdr.zaixianyouxi.dpdns.org/uploads/{year}/{month}/{year}{month}{day}.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/{year}/{0-month}/{year}{0-month}{0-day}.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/{year}/{0-month}/{0-day}/{year}{0-month}{0-day}.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/{year}/{month}/{day}/{year}{0-month}{0-day}.yaml
      // 生成结果
      https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/05/20260521.yaml
      https://sfdr.zaixianyouxi.dpdns.org/data/2026/5/20260521.txt
      https://api.abc.com/node/2026/05/20260521?auth=123
      https://test.xyz.com/path/2026/1/20260521](https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/5/2026521.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/05/20260521.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/05/21/20260521.yaml
      https://sfdr.zaixianyouxi.dpdns.org/uploads/2026/5/21/20260521.yaml
     ```
    
