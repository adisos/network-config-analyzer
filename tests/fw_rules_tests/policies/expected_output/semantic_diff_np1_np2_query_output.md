|query|src_ns|src_pods|dst_ns|dst_pods|connection|
|---|---|---|---|---|---|
|semantic_diff, config1: np1, config2: np2, key: Added connections between persistent peers and ipBlocks||||||
|||0.0.0.0-9.255.255.255|[kube-system]|[tier=frontend]|TCP 53|
|||11.0.0.0-172.20.255.255|[kube-system]|[tier=frontend]|TCP 53|
|||172.22.0.0-172.29.255.255|[kube-system]|[tier=frontend]|TCP 53|
|||172.31.0.0-255.255.255.255|[kube-system]|[tier=frontend]|TCP 53|
|semantic_diff, config1: np1, config2: np2, key: Removed connections between persistent peers and ipBlocks||||||
|||0.0.0.0-9.255.255.255|[kube-system]|[tier=frontend]|UDP 53|
|||11.0.0.0-172.20.255.255|[kube-system]|[tier=frontend]|UDP 53|
|||172.22.0.0-172.29.255.255|[kube-system]|[tier=frontend]|UDP 53|
|||172.31.0.0-255.255.255.255|[kube-system]|[tier=frontend]|UDP 53|

