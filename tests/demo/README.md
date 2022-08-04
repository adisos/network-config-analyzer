# NP-Guard Demo

### 1) Connectivity Visualization before adding Network Policies
    
```
git clone git@github.com:GoogleCloudPlatform/microservices-demo.git
cd microservices-demo
pip install network-config-analyzer
nca --connectivity -r release/ 
```

Consider various formats of connectivity reports:

```commandline
nca --connectivity -r release/ -o dot -f connectivity1.dot
```

```commandline
nca --connectivity -r release/ -o csv -f connectivity1.csv
```

```commandline
nca --connectivity -r release/ -o md -f connectivity1.md
```

```commandline
nca --connectivity -r release/ -o txt -f connectivity1.txt
```

### 2) Synthesis of Network Policies

```
./net-top -dirpath microservices-demo -netpols -outputfile release/netpols.yaml

```
### 3) Connectivity Visuzalization after adding Network Policies

```commandline
nca --connectivity -r release/ 
```




