# Hospital Coin Blockchain Explorer
This is a block explorer for the HOSP currency.

#### Installation

1) It takes data from daemon hospitald. It should be accessible from the Internet. Run hospitald with open port as follows:
```bash
./hospitald --enable-cors=* --enable_blockexplorer
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
