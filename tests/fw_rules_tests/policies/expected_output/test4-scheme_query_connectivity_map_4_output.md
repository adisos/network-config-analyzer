|query|src_ns|src_pods|dst_ns|dst_pods|connection|
|---|---|---|---|---|---|
|connectivity_map_4, config: np4||||||
||[kube-system-new-dummy-to-ignore]|[*]|[kube-system-new]|[*]|TCP 80-88|
||[ibm-system-new]|[*]|[kube-system-new]|[*]|TCP 80-90|
||[default]|[*]|[kube-system-new]|[*]|TCP 85-90|
|||0.0.0.0/0|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|
|||::/0|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]||0.0.0.0/0|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]||::/0|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|

|query|src_ns|src_pods|dst_ns|dst_pods|connection|
|---|---|---|---|---|---|
|connectivity_map_4, config: np3||||||
||[default]|[*]|[kube-system-new]|[*]|TCP 85-90|
|||0.0.0.0/0|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|
|||::/0|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]||0.0.0.0/0|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]||::/0|All connections|
||[default,ibm-system-new,kube-system-new,kube-system-new-dummy-to-ignore]|[*]|[default,ibm-system-new,kube-system-new-dummy-to-ignore]|[*]|All connections|

