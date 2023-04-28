## How to use Alpaca

### Interact on server

#### ssh connect to MIT server

```sh
ssh ganchuang@login.csail.mit.edu
ssh visiongpu55
```

"visiongpu55" can be any idle visiongpu

#### run Alpaca in conda

```sh
cd /data/vision/torralba/scratch/chuang/L/alpaca
source ~/.bashrc
conda activate alpaca
python my.py test.txt
```

Code above will run alpaca with prompt in test.txt for 5 times

### Interact with client

```Python
python client.py
```

Change the "text" attribute of request to use

Hint:

If the server is accidentally close,

run

```python
python server.py
```

in alpaca dir on MIT server.
