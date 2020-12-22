# 2020-20-L-test
Perf results

sysbench io

sysbench fileio run --threads=32 --file-async-backlog=1024  --file-num=25 --file-total-size=100G --file-io-mode=async --file-test-mode=rndrw --file-extra-flags=direct --time=3600 --report-interval=1 --file-fsync-freq=0  --file-fsync-end=off 
