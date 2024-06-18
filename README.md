# makeusers
Create username pattern based on Name and Second name

## Usage

```bash
❯ wget https://raw.githubusercontent.com/0xbara/makeusers/main/makeusers -O makeusers
❯ chmod +x makeusers

❯ cat names.txt

Ruy Alonso
Maya Bendito
Gregory Smith

❯ ./makeusers names.txt > usernames.txt

❯ cat usernames.txt

ruyalonso
ruy.alonso
ralonso
r.alonso
ruya
ruy.a
alonsoruy
alonso.ruy
aruy
a.ruy
alonsor
alonso.r
mayabendito
maya.bendito
mbendito
m.bendito
mayab
maya.b
benditomaya
bendito.maya
bmaya
b.maya
benditom
bendito.m
gregorysmith
gregory.smith
gsmith
g.smith
gregorys
gregory.s
smithgregory
smith.gregory
sgregory
s.gregory
smithg
smith.g
```
