# wick

This small [Typst](https://typst.app/) package handles the typesetting of [Wick contractions](https://en.wikipedia.org/wiki/Wick%27s_theorem). Read `docs.pdf` for more information. 

<div style="text-align: center; margin-top: 40px; margin-bottom: 15px;">
<img src="images/example.png" width="500" alt="Example"/>
</div>

```typ
$ :
wick(id: #1, overline(Psi))_alpha (x)
gamma^mu_(alpha beta) 
wick(pos: #top, A)_mu (x) 
wick(Psi)_beta (x)
wick(overline(Psi))_eta (y)
gamma^nu_(eta rho) (y)
wick(pos: #top, A)_nu 
wick(id: #1, Psi)_rho (y)
: $
```