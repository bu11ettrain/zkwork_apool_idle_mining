
# ALEO + QUBIC Idle Mining on ZK.Work + apool.io

#### HiveOS:

1. Add **QUBIC** wallet in HiveOS
<img src="img/hiveos_wal_example.png" style="width:500px;"/>

2. Add and setup new Flight sheet
<img src="img/hiveos_fs_example_1.png" style="width:800px;"/>
<img src="img/hiveos_fs_example_2.png" style="width:500px;"/>

* Miner name: `zkwork_apool_idle_mining`
* Installation URL: `https://github.com/bu11ettrain/zkwork_apool_idle_mining/releases/download/v1.0/zkwork_apool_idle_mining-v1.0_hiveos.tar.gz`
* Wallet and worker template:`%WAL`
* Pool URL：`qubic2.hk.apool.io:3334`
* Extra Config Arguments: `--worker %WORKER_NAME% --cpu-off`
* Pass：`--pool aleo.eu.zk.work:10003 --pool aleo.asia1.zk.work:10003 --pool aleo.hk.zk.work:10003 --pool aleo.jp.zk.work:10003 --pool aleo.eu.zk.work:10003 --custom_name %WORKER_NAME% --address aleoxxx`

Don't forget to replace `aleoxxx` with your **ALEO** wallet address.
