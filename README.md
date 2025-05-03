# Hadoop

角色：分散式儲存 + 批次資料處理的基礎建設。

核心組件：

HDFS（Hadoop Distributed File System）：類似雲端硬碟，讓你把大檔案切割儲存在不同節點。

MapReduce：一種資料處理框架，將任務分成 Map 與 Reduce 兩階段。

優點：可水平擴展、處理超大批次資料。

限制：MapReduce 效率不如 Spark，無法處理實時任務。
