- 👋 Hi, I’m @davRonkhakimov
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
davRonkhakimov/davRonkhakimov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def oraliq(min, max, qadam=''):
    sonlar = []
    while min < max:
        if qadam:
            min += qadam
        else:
            min += 1
        sonlar.append(min)

    return sonlar


son = oraliq(0, 10,2 )
print(son)
