# simtext
simtext, the most accurate Chinese text similarity calculation tool.(最准的中文文本相似度计算工具)

## Install
* pip3 install simtext

or

```
git clone https://github.com/shibing624/simtext.git
cd simtext
python3 setup.py install
```

## Usage:
```
from simtext import Similarity

sim = Similarity()
a = '湖北人爱吃鱼'
b = '甘肃人不爱吃鱼'
s = sim.score(a, b)
print(s)

```

output:
```
0.966466890301913
```
