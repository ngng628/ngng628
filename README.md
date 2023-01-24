
<div align="center">

👻💎👻<br>
*who ya gonna call?*

</div>

#

[![Rating](https://badgen.org/img/atcoder/ngng628/rating/algorithm?style=for-the-badge&label=RATING%28ALGO%29)](https://atcoder.jp/users/ngng628?contestType=algo)
[![Rating(Heuristic)](https://badgen.org/img/atcoder/ngng628/rating/heuristic?style=for-the-badge)](https://atcoder.jp/users/ngng628?contestType=heuristic)

![manjaro](https://img.shields.io/badge/manjaro-35BF5C?style=for-the-badge&logo=manjaro&logoColor=white)

## $\mathcal{who\ am\ I?}$

- 🐦 https://twitter.com/ngng628
- :octocat: https://github.com/ngng628
- 🪵 https://scrapbox.io/ngmemo/
- 🏇 https://atcoder.jp/users/ngng628
- 📊 https://codeforces.com/profile/ngng628

## $\mathcal{GitHub\ Stats}$

<table>
  <tr>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=ngng628&count_private=true&show_icons=true&theme=dracula&bg_color=00000000&hide_border=true" />
      </a>
    </td>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ngng628&layout=compact&langs_count=10&theme=dracula&bg_color=00000000&hide_border=true" />
      </a>
    </td>
  </tr>
</table>
</div>

## $\mathcal{Fizz Buzz}$

```cr
n = (1..100).select { |i| i % 3 == 0 }.map { |i| { i, "Fizz" } }
g = (1..100).select { |i| i % 5 == 0 }.map { |i| { i, "Buzz" } }
n = n.concat(g).group_by(&.[0]).map { |i, s| {i, s.sum("", &.[1])} }
g = n.concat([*(1..100)].map{ |i| {i, i.to_s} }).uniq(&.[0]).sort.map(&.[1]); puts [
6_2,8].map(&.chr).join + g.join(" ") # => 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz ...
```
