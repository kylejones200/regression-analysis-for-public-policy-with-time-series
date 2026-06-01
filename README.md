# Repository

Companion code for a Medium article.

## Business context

Regression analysis is the backbone of econometric analysis and is central to public policy evaluation. It quantifies the relationship between dependent and independent variables, enabling policymakers to estimate causal impacts, forecast outcomes, and make data-driven decisions. The simplest form of regression is the Ordinary Least Squares (OLS) linear regression, defined as:

The objective is to minimize the sum of squared residuals: $$min sum_{i=1}^{n} (Y_i - beta_0 - beta_1 X_i)^2$$

The OLS estimators are calculated as: $$hat{beta}_1 = frac{sum (X_i - bar{X})(Y_i - bar{Y})}{sum (X_i - bar{X})^2}$$ $$hat{beta}_0 = bar{Y} - hat{beta}_1 bar{X}$$

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).