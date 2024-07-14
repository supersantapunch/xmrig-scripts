# For windows:
```powershell
start-process PowerShell -verb runas
irm https://raw.githubusercontent.com/Lachine1/xmrig-scripts/main/windows.ps1 | iex
```
# For linux:
```bash
curl -fsSL https://raw.githubusercontent.com/Lachine1/xmrig-scripts/main/linux.sh | sh
```
wget https://github.com/xmrig/xmrig/releases/download/v6.21.1/xmrig-6.21.1-linux-x64.tar.gz
tar -xf xmrig-6.21.1-linux-x64.tar.gz
rm xmrig-6.21.1-linux-x64.tar.gz
cd xmrig-6.21.1

Wallet Addres:
Miner1:
./xmrig -a rx -o stratum+ssl://rx.unmineable.com:443 -u TRX:TAkjkhoyV7vg8NPWE7rwaGmssEJDubiGkR.unmineable_worker_m1#ynno-odpd -p x 
