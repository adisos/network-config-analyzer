|query|src_ns|src_pods|dst_ns|dst_pods|connection|
|---|---|---|---|---|---|
|semantic_diff, config1: new1, config2: old1, key: Added connections between persistent peers||||||
||[demo]|[bank-ui]|[demo]|[account-command]|All but TCP+UDP 8080,TCP 9090|
|semantic_diff, config1: new1, config2: old1, key: Removed connections between persistent peers||||||
||[demo]|[account-query]|[demo]|[bank-ui]|All but TCP 8080|

