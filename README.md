# Latex symbols template (2.0.11)
Short symbol commands for <img src="https://latex.codecogs.com/gif.latex?\LaTeX" title="\LaTeX" /></br>
Warning Note: Not backward compatible with anything before version 2.0.00.

### Installation and usage:
1. Download the `symbols.tex` file and put is in the same folder as that of the main `.tex` file.
2. Add `\input{symbols.tex}` after all `\usepackage{}` headers in the main `.tex` file.
3. Refer to `test.tex` and `test.pdf` for further help.


### Required packages (included):
1. `algorithm`
2. `amsmath`
3. `amsthm`
4. `amssymb`
5. `dsfont`
6. `algpseudocode`
7. `thmtools`
8. `xcolor`


### Available environments:
1. `Theorem`
2. `Definition`
3. `Proposition`
4. `Lemma`
5. `Corollary`
6. `Example`
7. `Remark`
8. `Subsec`


### Extras in algorithms:
If you use `algorithmic` inside `algorithm` environment,
1. All the following introductory commands are valid
	a. using `\Require` will result into `Require:`
	b. using `\Ensure` will result into `Ensure:`
	c. using `\Input` will result into `Input:`
	d. using `\Init` will result into `Initialize:`
	e. using `\Output` will result into `Output:`
2. `\Print` and `\To` commands are compatible with required packages


### Table of usage:
#### Lower case bold English alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\ba` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{a}" /> | `\bb` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{b}" /> | `\bc` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{c}" /> | `\bd` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{d}" /> |
| `\be` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{e}" /> | `\bdf` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{f}" /> | `\bg` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{g}" /> | `\bh` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{h}" /> |
| `\bi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{i}" /> | `\bj` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{j}" /> | `\bk` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{k}" /> | `\bl` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{l}" /> |
| `\bm` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{m}" /> | `\bn` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{n}" /> | `\bo` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{o}" /> | `\bp` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{p}" /> |
| `\bq` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{q}" /> | `\br` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{r}" /> | `\bs` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{s}" /> | `\bt` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{t}" /> |
| `\bu` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{u}" /> | `\bv` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{v}" /> | `\bw` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{w}" /> | `\bx` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{x}" /> |
| `\by` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{y}" /> | `\bz` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{z}" /> |


#### Upper case bold English alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\bA` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{A}" /> | `\bB` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{B}" /> | `\bC` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{C}" /> | `\bD` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{D}" /> |
| `\bE` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{E}" /> | `\bF` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{F}" /> | `\bG` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{G}" /> | `\bH` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{H}" /> |
| `\bI` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{I}" /> | `\bJ` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{J}" /> | `\bK` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{K}" /> | `\bL` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{L}" /> |
| `\bM` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{M}" /> | `\bN` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{N}" /> | `\bO` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{O}" /> | `\bP` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{P}" /> |
| `\bQ` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{Q}" /> | `\bR` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{R}" /> | `\bS` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{S}" /> | `\bT` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{T}" /> |
| `\bU` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{U}" /> | `\bV` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{V}" /> | `\bW` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{W}" /> | `\bX` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{X}" /> |
| `\bY` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{Y}" /> | `\bZ` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{Z}" /> |


#### Bold Greek alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\balpha` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\alpha}" /> | `\bbeta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\beta}" /> | `\bgamma` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\gamma}" /> | `\bGamma` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Gamma}" /> |
| `\bdelta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\delta}" /> | `\bDelta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Delta}" /> | `\bepsilon` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\epsilon}" /> | `\bvarepsilon` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\varepsilon}" /> |
| `\bzeta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\zeta}" /> | `\bdeta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\eta}" /> | `\btheta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\theta}" /> | `\bvartheta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\vartheta}" /> |
| `\bTheta` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Theta}" /> | `\biota` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\iota}" /> | `\bkappa` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\kappa}" /> | `\blambda` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\lambda}" /> |
| `\bLambda` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Lambda}" /> | `\bmu` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\mu}" /> | `\bnu` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\nu}" /> | `\bxi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\xi}" /> |
| `\bXi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Xi}" /> | `\bpi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\pi}" /> | `\bPi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Pi}" /> | `\brho` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\rho}" /> |
| `\bvarrho` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\varrho}" /> | `\bsigma` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\sigma}" /> | `\bSigma` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Sigma}" /> | `\btau` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\tau}" /> |
| `\bupsilon` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\upsilon}" /> | `\bUpsilon` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Upsilon}" /> | `\bphi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\phi}" /> | `\bvarphi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\varphi}" /> |
| `\bPhi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Phi}" /> | `\bchi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\chi}" /> | `\bpsi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\psi}" /> | `\bPsi` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Psi}" /> |
| `\bomega` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\omega}" /> | `\bOmega` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{\Omega}" /> |


#### Mathbf lower case English alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\mba` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{a}" /> | `\mbb` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{b}" /> | `\mbc` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{c}" /> | `\mbd` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{d}" /> |
| `\mbe` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{e}" /> | `\mbf` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{f}" /> | `\mbg` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{g}" /> | `\mbh` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{h}" /> |
| `\mbi` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{i}" /> | `\mbj` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{j}" /> | `\mbk` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{k}" /> | `\mbl` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{l}" /> |
| `\mbm` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{m}" /> | `\mbn` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{n}" /> | `\mbo` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{o}" /> | `\mbp` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{p}" /> |
| `\mbq` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{q}" /> | `\mbr` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{r}" /> | `\mbs` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{s}" /> | `\mbt` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{t}" /> |
| `\mbu` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{u}" /> | `\mbv` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{v}" /> | `\mbw` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{w}" /> | `\mbx` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{x}" /> |
| `\mby` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{y}" /> | `\mbz` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{z}" /> |


#### Mathbf upper case English alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\mbA` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{A}" /> | `\mbB` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{B}" /> | `\mbC` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{C}" /> | `\mbD` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{D}" /> |
| `\mbE` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{E}" /> | `\mbF` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{F}" /> | `\mbG` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{G}" /> | `\mbH` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{H}" /> |
| `\mbI` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{I}" /> | `\mbJ` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{J}" /> | `\mbK` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{K}" /> | `\mbL` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{L}" /> |
| `\mbM` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{M}" /> | `\mbN` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{N}" /> | `\mbO` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{O}" /> | `\mbP` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{P}" /> |
| `\mbQ` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{Q}" /> | `\mbR` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{R}" /> | `\mbS` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{S}" /> | `\mbT` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{T}" /> |
| `\mbU` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{U}" /> | `\mbV` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{V}" /> | `\mbW` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{W}" /> | `\mbX` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{X}" /> |
| `\mbY` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{Y}" /> | `\mbZ` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{Z}" /> |


#### Caligraphy upper case English alphabets
| Syntax | Description | Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\calA` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{A}" /> | `\calB` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{B}" /> | `\calC` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{C}" /> | `\calD` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{D}" /> |
| `\calE` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{E}" /> | `\calF` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{F}" /> | `\calG` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{G}" /> | `\calH` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{H}" /> |
| `\calI` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{I}" /> | `\calJ` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{J}" /> | `\calK` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{K}" /> | `\calL` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{L}" /> |
| `\calM` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{M}" /> | `\calN` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{N}" /> | `\calO` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{O}" /> | `\calP` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{P}" /> |
| `\calQ` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{Q}" /> | `\calR` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{R}" /> | `\calS` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{S}" /> | `\calT` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{T}" /> |
| `\calU` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{U}" /> | `\calV` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{V}" /> | `\calW` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{W}" /> | `\calX` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{X}" /> |
| `\calY` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{Y}" /> | `\calZ` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{Z}" /> |


#### Numbers
| Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- |
| `\bzero` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{0}" /> | `\bone` | <img src="https://latex.codecogs.com/gif.latex?\boldsymbol{1}" /> |


#### Sets
| Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\binaryB{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{B}^N" /> | `\complexC{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{C}^N" /> | `\expecE{\bx}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{E}\{\boldsymbol{x}\}" /> |
| `\naturalN{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{N}^N" /> | `\probP{\bx}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{P}\mathrm{r}\{\boldsymbol{x}\}" /> | `\rationalQ{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{Q}^N" /> |
| `\realR{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{R}^N" /> | `\realRp{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{R}_{+}^N" /> | `\realRn{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{R}_{-}^N" /> |
| `\integerZ{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathbb{Z}^N" /> |


#### Matrix terms
| Syntax | Description | Syntax | Description | Syntax | Description | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\tr{X}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{Tr}(X)" /> | `\vec{X}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{vec}(X)" /> | `\diag{X}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{diag}(X)" /> |
| `\Diag{\bx}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{Diag}(\boldsymbol{x})" /> | `\bdiag{X}` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{diag}(X)" /> | `\cov{\bx}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{cov}(\boldsymbol{x})" /> |
| `\Cov{X}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{Cov}(X)" /> | `\bcov{x}` | <img src="https://latex.codecogs.com/gif.latex?\mathbf{cov}(x)" /> |


#### Misc.
| Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\asin{x}` | <img src="https://latex.codecogs.com/gif.latex?\sin^{-1}(x)" /> | `\acos{x}` | <img src="https://latex.codecogs.com/gif.latex?\cos^{-1}(x)" /> | `\atan{x}` | <img src="https://latex.codecogs.com/gif.latex?\tan^{-1}(x)" /> |
| `\acsc{x}` | <img src="https://latex.codecogs.com/gif.latex?\csc^{-1}(x)" /> | `\asec{x}` | <img src="https://latex.codecogs.com/gif.latex?\sec^{-1}(x)" /> | `\acot{x}` | <img src="https://latex.codecogs.com/gif.latex?\cot^{-1}(x)" /> |
| `\implies` | <img src="https://latex.codecogs.com/gif.latex?\Rightarrow" /> | `\half` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{2}" /> | `\roothalf` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{\sqrt{2}}" /> |
| `\third` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{3}" /> | `\quarter` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{4}" /> | `\fourth` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{4}" /> |
| `\fifth` | <img src="https://latex.codecogs.com/gif.latex?\frac{1}{5}" /> | `\threequarter` | <img src="https://latex.codecogs.com/gif.latex?\frac{3}{4}" /> | `\ejomg` | <img src="https://latex.codecogs.com/gif.latex?e^{j\omega}" /> |
| `\ejnomg` | <img src="https://latex.codecogs.com/gif.latex?e^{-j\omega}" /> | `\zinv` | <img src="https://latex.codecogs.com/gif.latex?z^{-1}" /> | `\sgn{x}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{sgn}(x)" /> |
| `\sign{x}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{sign}(x)" /> | `\csign{x}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{csign}(x)" /> | `X\deg` | <img src="https://latex.codecogs.com/gif.latex?X^\circ" /> |
| `\Oh{N}` | <img src="https://latex.codecogs.com/gif.latex?\mathcal{O}(N)" /> | `\oh{N}` | <img src="https://latex.codecogs.com/gif.latex?o(N)" /> | `\st` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{s.t.}" /> |
| `\ow` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{otherwise}" /> | `\ew` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{elsewhere}" /> | `\eg` | <img src="https://latex.codecogs.com/gif.latex?\textit{e.g.}" /> |
| `\ie` | <img src="https://latex.codecogs.com/gif.latex?\textit{i.e.}" /> | `\etal` | <img src="https://latex.codecogs.com/gif.latex?\textit{et%20al.}" /> | `\etc` | <img src="https://latex.codecogs.com/gif.latex?\textit{etc.}" /> |
| `\viz` | <img src="https://latex.codecogs.com/gif.latex?\textit{viz.}" /> | `\d{y}` | <img src="https://latex.codecogs.com/gif.latex?\mathrm{d}y" /> | `\conv` | <img src="https://latex.codecogs.com/gif.latex?\circledast" /> |

#### Basic text colors
| Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\white{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{white}\text{text}" /> | `\black{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{black}\text{text}" /> | `\red{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{red}\text{text}" /> |
| `\green{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{green}\text{text}" /> | `\blue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{blue}\text{text}" /> | `\cyan{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{cyan}\text{text}" /> | 
| `\magenta{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{magenta}\text{text}" /> | `\yellow{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{yellow}\text{text}" /> |


#### Special colors that comes with [dvipsnames] option in xcolor package (included)
| Syntax | Description | Syntax | Description | Syntax | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| `\Apricot{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Apricot}\text{text}" /> | `\Aquamarine{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Aquamarine}\text{text}" /> | `\Bittersweet{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Bittersweet}\text{text}" /> |
| `\Black{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Black}\text{text}" /> | `\Blue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Blue}\text{text}" /> | `\BlueGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{BlueGreen}\text{text}" /> | 
| `\BlueViolet{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{BlueViolet}\text{text}" /> |`\BrickRed{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{BrickRed}\text{text}" /> | `\Brown{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Brown}\text{text}" /> | 
| `\BurntOrange{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{BurntOrange}\text{text}" /> | `\CadetBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{CadetBlue}\text{text}" /> |`\CarnationPink{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{CarnationPink}\text{text}" /> |
| `\Cerulean{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Cerulean}\text{text}" /> | `\CornflowerBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{CornflowerBlue}\text{text}" /> | `\Cyan{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Cyan}\text{text}" /> |
| `\Dandelion{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Dandelion}\text{text}" /> | `\DarkOrchid{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{DarkOrchid}\text{text}" /> | `\Emerald{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Emerald}\text{text}" /> | 
| `\ForestGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{ForestGreen}\text{text}" /> |`\Fuchsia{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Fuchsia}\text{text}" /> | `\Goldenrod{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Goldenrod}\text{text}" /> | 
| `\Gray{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Gray}\text{text}" /> | `\Green{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Green}\text{text}" /> |`\GreenYellow{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{GreenYellow}\text{text}" /> |
| `\JungleGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{JungleGreen}\text{text}" /> | `\Lavender{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Lavender}\text{text}" /> | `\LimeGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{LimeGreen}\text{text}" /> |
| `\Magenta{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Magenta}\text{text}" /> | `\Mahogany{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Mahogany}\text{text}" /> | `\Maroon{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Maroon}\text{text}" /> |
| `\Melon{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Melon}\text{text}" /> |`\MidnightBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{MidnightBlue}\text{text}" /> | `\Mulberry{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Mulberry}\text{text}" /> | 
| `\NavyBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{NavyBlue}\text{text}" /> | `\OliveGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{OliveGreen}\text{text}" /> |`\Orange{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Orange}\text{text}" /> |
| `\OrangeRed{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{OrangeRed}\text{text}" /> | `\Orchid{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Orchid}\text{text}" /> | `\Peach{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Peach}\text{text}" /> |
| `\Periwinkle{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Periwinkle}\text{text}" /> | `\PineGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{PineGreen}\text{text}" /> | `\Plum{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Plum}\text{text}" /> | 
| `\ProcessBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{ProcessBlue}\text{text}" /> |`\Purple{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Purple}\text{text}" /> | `\RawSienna{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RawSienna}\text{text}" /> | 
| `\Red{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Red}\text{text}" /> | `\RedOrange{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RedOrange}\text{text}" /> |`\RedViolet{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RedViolet}\text{text}" /> |
| `\Rhodamine{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Rhodamine}\text{text}" /> | `\RoyalBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RoyalBlue}\text{text}" /> | `\RoyalPurple{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RoyalPurple}\text{text}" /> |
| `\RubineRed{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{RubineRed}\text{text}" /> | `\Salmon{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Salmon}\text{text}" /> | `\SeaGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{SeaGreen}\text{text}" /> | 
| `\Sepia{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Sepia}\text{text}" /> |`\SkyBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{SkyBlue}\text{text}" /> | `\SpringGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{SpringGreen}\text{text}" /> | 
| `\Tan{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Tan}\text{text}" /> | `\TealBlue{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{TealBlue}\text{text}" /> |`\Thistle{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Thistle}\text{text}" /> |
| `\Turquoise{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Turquoise}\text{text}" /> | `\Violet{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Violet}\text{text}" /> | `\VioletRed{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{VioletRed}\text{text}" /> |
| `\White{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{White}\text{text}" /> | `\WildStrawberry{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{WildStrawberry}\text{text}" /> | `\Yellow{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{Yellow}\text{text}" /> | 
| `\YellowGreen{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{YellowGreen}\text{text}" /> |`\YellowOrange{text}` | <img src="https://latex.codecogs.com/gif.latex?\color{YellowOrange}\text{text}" /> |
