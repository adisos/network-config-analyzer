|query|src_ns|src_pods|dst_ns|dst_pods|connection|
|---|---|---|---|---|---|
|semantic_diff, config1: config_a, config2: config_b, key: Lost connections between removed peers||||||
||[default]|[app=app-3]|[default]|[app=app-4]|All connections|
||[default]|[app=app-4]|[default]|[app=app-3]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Lost connections between removed peers and ipBlocks||||||
|||0.0.0.0/0|[default]|[app in (app-3,app-4)]|All connections|
|||::/0|[default]|[app in (app-3,app-4)]|All connections|
||[default]|[app in (app-3,app-4)]||0.0.0.0/0|All connections|
||[default]|[app in (app-3,app-4)]||::/0|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Lost connections between removed peers and persistent peers||||||
||[default]|[app in (app-3,app-4)]|[default]|[app in (app-0,app-2)]|All connections|
||[default]|[app not in (app-3,app-4)]|[default]|[app in (app-3,app-4)]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Added connections between persistent peers||||||
||[default]|[app=app-0]|[default]|[app=app-1]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Removed connections between persistent peers||||||
||[default]|[app=app-0]|[default]|[app=app-2]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Added connections between persistent peers and ipBlocks||||||
|||0.0.0.0/0|[default]|[app=app-1]|All connections|
|||::/0|[default]|[app=app-1]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: Removed connections between persistent peers and ipBlocks||||||
|||0.0.0.0/0|[default]|[app=app-2]|All connections|
|||::/0|[default]|[app=app-2]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: New connections between persistent peers and added peers||||||
||[default]|[app in (app-5,app-6)]|[default]|[app in (app-0,app-1)]|All connections|
||[default]|[app not in (app-5,app-6)]|[default]|[app in (app-5,app-6)]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: New connections between added peers||||||
||[default]|[app=app-5]|[default]|[app=app-6]|All connections|
||[default]|[app=app-6]|[default]|[app=app-5]|All connections|
|semantic_diff, config1: config_a, config2: config_b, key: New connections between added peers and ipBlocks||||||
|||0.0.0.0/0|[default]|[app in (app-5,app-6)]|All connections|
|||::/0|[default]|[app in (app-5,app-6)]|All connections|
||[default]|[app in (app-5,app-6)]||0.0.0.0/0|All connections|
||[default]|[app in (app-5,app-6)]||::/0|All connections|

