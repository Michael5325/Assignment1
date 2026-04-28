# Assignment1
First class assignment
# PGA Championship Recent Winners

![PGA Championship Trophy]([https://upload.wikimedia.org/wikipedia/commons/8/8f/Wanamaker_Trophy.jpg)](https://images.ctfassets.net/56u5qdsjym8c/6PCUu4bijvdASwxxlUkiKn/f36ffe0322bb24c57bc702d2877809e6/VHGC.06.07.22.8609.jpg?fl=progressive&q=80)

## Overview

The **PGA Championship** is one of golf’s four major championships, featuring the best professional golfers in the world. This README highlights *recent champions* and provides a small code example for working with the data programmatically. 

---

## Recent PGA Championship Winners

### Champions 2021–2024

- **2024:** *Xander Schauffele* — Valhalla G.C.  
- **2023:** *Brooks Koepka* — Oak Hill C.C.  
- **2022:** *Justin Thomas* — Southern Hills C.C.  
- **2021:** *Phil Mickelson* — Kiawah Island  

These winners reflect a mix of established stars and remarkable comebacks, including Mickelson’s historic victory as the oldest PGA champion. 

---

## More information

For full historical results and stats, visit the  
<u>[[Official PGA Championship page](https://www.pgachampionship.com)](https://www.pgachampionship.com/)</u>.

---

## Example code

### Sample JSON of recent winners

```python
pga_winners = [
    {"year": 2024, "winner": "Xander Schauffele", "course": "Valhalla G.C."},
    {"year": 2023, "winner": "Brooks Koepka", "course": "Oak Hill C.C."},
    {"year": 2022, "winner": "Justin Thomas", "course": "Southern Hills C.C."},
    {"year": 2021, "winner": "Phil Mickelson", "course": "Kiawah Island"},
]

for entry in pga_winners:
    print(f"{entry['year']}: {entry['winner']} at {entry['course']}")
