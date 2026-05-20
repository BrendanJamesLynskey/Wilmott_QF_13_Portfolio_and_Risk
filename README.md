# Portfolio Management, VaR &amp; Risk

Deck 13 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_13_Portfolio_and_Risk/

A guided tour of chapters 20 through 26 of *Paul Wilmott Introduces Quantitative Finance*
(2nd edition, Wiley, 2007) &mdash; from gambling and the Kelly criterion through Modern
Portfolio Theory, CAPM, Value at Risk, credit risk, copulas, and the disasters
that taught the industry to take risk management seriously.

## What's inside

- Gambling lessons: blackjack, the Kelly criterion $f^* = (p(b+1)-1)/b$, sports arbitrage
- Diversification &mdash; "the only free lunch in finance"
- Modern Portfolio Theory: the efficient frontier, minimum-variance and tangency portfolios
- CAPM: $\mathbb{E}[R_i] = R_f + \beta_i (\mathbb{E}[R_M] - R_f)$ and what $\beta$ measures
- Parametric VaR: $\mathrm{VaR}_\alpha = -\mu + \sigma z_\alpha$; coherence, ES, FRTB
- VaR for derivatives: delta, delta&ndash;gamma, full Monte Carlo
- Credit risk &mdash; the Merton model: equity as a call on firm assets
- Reduced-form default: Poisson intensity $\lambda(t)$, risky-bond pricing $B = e^{-(r+\lambda)T}$
- Copulas, CrashMetrics and a tour of derivative disasters (Orange County, Barings, LTCM, 2008, London Whale)
- **Interactive efficient frontier &amp; VaR explorer** &mdash; two-asset portfolio with sliders for $\mu_1, \mu_2, \sigma_1, \sigma_2, \rho, w_1$, reading off portfolio mean, vol, 95% / 99% VaR and Sharpe ratio, with the frontier plotted on the left and the shaded VaR region on the return PDF on the right

Companion to chapters 20&ndash;26 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
