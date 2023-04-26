## How to use Alpaca
### ssh connect to MIT server
```sh
ssh ganchuang@login.csail.mit.edu(password:~ganchuang90)
ssh visiongpu55
```
"visiongpu55" can be any idle visiongpu
### run Alpaca in conda
```sh
cd /data/vision/torralba/scratch/chuang/L/alpaca
source ~/.bashrc
conda activate alpaca
python my.py test.txt
```
Code above will run alpaca with prompt in test.txt for 5 times
