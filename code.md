---
title: code
---

## Constrained adaptive sensing

This software package contains code that  can be used to select an optimal
set  of  measurements for  sensing  a  sparse  vector in  the  constrained
setting. For  further  details,  see   the  paper  "[Constrained  adaptive
sensing][1],"   by  M. A. Davenport,   A. K. Massimino,  D. Needell,   and
T. Woolf.

```
{% include dmnw-tsp-2016.bib -%}
```

The code can  be downloaded [here][2]; see the included readme file for a
detailed description of the contents and for usage instructions.

## ![vim]({{ site.url }}/images/vim_on_fire.gif){:height="42px"}

I wrote and maintain a couple of vim plugins:
- [match-up][mu]: allows you to highlight, navigate between, and operate
  on sets of matching language text (e.g., `\begin{}` and `\end{}`
  in LaTeX).
  [![stars][mu-st]{:.v-mid}][mu]
- [trade-winds][tw]: more easily move windows in complex layouts and
  convert between vertical and horizontal splits.
  [![stars][tw-st]{:.v-mid}][tw]

I have also had a few patches accepted into [vim itself][6].

## More...

See my repositories at [@andymass][3] on github.

[1]: https://arxiv.org/abs/1506.05889
[2]: http://mdav.ece.gatech.edu/software/constrained-adaptive-code.zip
[3]: https://github.com/andymass

[mu]: https://github.com/andymass/vim-matchup
[mu-st]: https://img.shields.io/github/stars/andymass/vim-matchup.svg?style=social
[tw]: https://github.com/andymass/vim-tradewinds
[tw-st]: https://img.shields.io/github/stars/andymass/vim-tradewinds.svg?style=social

[6]: https://github.com/vim/vim/search?q=massimino&type=Commits

