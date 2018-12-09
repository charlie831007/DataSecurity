# DataSecurity

Paper主要差異為不做upload，造成影響如下：
1. 若檢查的chunk有重複無法dedup.
2. dirty chunk無法被清空
3. 超過threshold的chunk依舊無法被dedup.
