
<div align="center">

👻💎👻<br>
*who ya gonna call?*

</div>

#

[![Rating](https://badgen.org/img/atcoder/ngng628/rating/algorithm?style=for-the-badge&label=RATING%28ALGO%29)](https://atcoder.jp/users/ngng628?contestType=algo)
[![Rating(Heuristic)](https://badgen.org/img/atcoder/ngng628/rating/heuristic?style=for-the-badge)](https://atcoder.jp/users/ngng628?contestType=heuristic)

![manjaro](https://img.shields.io/badge/manjaro-35BF5C?style=for-the-badge&logo=manjaro&logoColor=white)

## $\mathcal{GitHub\ Stats}$

<div align="center">

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ngng628&count_private=true&theme=dracula)

</div>

## $\mathcal{Languages}$

<div align="center">

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ngng628&layout=compact&theme=dracula)](https://github.com/anuraghazra/github-readme-stats)

</div>

## $\mathcal{Fizz Buzz}$

```cr
n = (1..15).select { |i| i % 3 == 0 }.map { |i| { i, "Fizz" } }
g = (1..15).select { |i| i % 5 == 0 }.map { |i| { i, "Buzz" } }
n = n.concat(g).group_by(&.[0]).map { |i, s| {i, s.sum("", &.[1])} }
g = n.concat([*(1..15)].map{ |i| {i, i.to_s} }).uniq(&.[0]).sort.map(&.[1]); puts [
6_2,8].map(&.chr).join + g.join(" ") # => 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz
```
