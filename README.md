
<div align="center">

👻👻<br>
*who ya gonna call?*

</div>

#

[![ngng628](https://img.shields.io/endpoint?url=https%3A%2F%2Fatcoder-badges.now.sh%2Fapi%2Fatcoder%2Fjson%2Fngng628)](https://atcoder.jp/users/ngng628)
[![ngng628](https://img.shields.io/endpoint?url=https%3A%2F%2Fatcoder-badges.now.sh%2Fapi%2Fcodeforces%2Fjson%2Fngng628)](https://codeforces.com/profile/ngng628)

![manjaro](https://img.shields.io/badge/manjaro-35BF5C?style=for-the-badge&logo=manjaro&logoColor=white)

## $\mathcal{Who\ am\ I?}$

- 👨‍💻 https://ngng628.github.io/portfolio/
- 🐦 https://twitter.com/ngng628
- :octocat: https://github.com/ngng628
- 🪵 https://scrapbox.io/ngmemo/
- 🏇 https://atcoder.jp/users/ngng628
- 📊 https://codeforces.com/profile/ngng628

## $\mathcal{GitHub\ Stats}$

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api?username=ngng628&count_private=true&show_icons=true&theme=dracula&bg_color=00000000&hide_border=true" />
</a>

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ngng628&layout=compact&langs_count=10&theme=dracula&bg_color=00000000&hide_border=true" />
</a>

## $\mathcal{Fizz Buzz}$

```cr
n = (1..100).select { |i| i % 3 == 0 }.map { |i| { i, "Fizz" } }
g = (1..100).select { |i| i % 5 == 0 }.map { |i| { i, "Buzz" } }
n = n.concat(g).group_by(&.[0]).map { |i, s| {i, s.sum("", &.[1])} }
g = n.concat([*(1..100)].map{ |i| {i, i.to_s} }).uniq(&.[0]).sort.map(&.[1]); puts [
6_2,8].map(&.chr).join + g.join(" ") # => 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz ...
```
