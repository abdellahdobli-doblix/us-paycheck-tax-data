# US paycheck and local tax data (2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24421615.svg)](https://doi.org/10.5281/zenodo.24421615)

Free CSV data behind the calculators at [Dolidob](https://dolidob.com/data/). Every official figure is checked against a government source.

| File | Rows | What it holds |
|---|---|---|
| [take-home-pay-by-state-2026.csv](take-home-pay-by-state-2026.csv) | 2,295 | Federal tax, Social Security, Medicare, state tax, state employee contributions and take-home pay, by state (and DC) and salary. Single filer, paid every two weeks, no 401(k). |
| [take-home-pay-by-state-2026-married-joint.csv](take-home-pay-by-state-2026-married-joint.csv) | 2,295 | The same for married filing jointly, one spouse earning the salary and the other with no wages; state withholding form defaults as in the calculator (California 1 DE 4 allowance, Oregon OR-W-4 Married). |
| [us-local-income-tax-rates.csv](us-local-income-tax-rates.csv) | 789 | City and county wage taxes in MI, IN, MD, NY, PA and OH, with resident and nonresident rates and the official source for each row |
| [ohio-municipal-income-tax-rates.csv](ohio-municipal-income-tax-rates.csv) | 667 | Every Ohio municipality with an income tax (Ohio Department of Taxation) |
| [federal-income-tax-brackets.csv](federal-income-tax-brackets.csv) | 56 | 2026 and 2027 federal brackets and standard deductions (IRS Rev. Proc. 2025-32 and 2026-35) |

Column definitions, versions and sources are in [datapackage.json](datapackage.json) (Frictionless Data Package).
The latest version of every file is always at https://dolidob.com/data/.
Also on [Kaggle](https://www.kaggle.com/datasets/dobliabdellah/us-take-home-pay-and-local-income-tax-rates-2026) and [Hugging Face](https://huggingface.co/datasets/didox33/us-take-home-pay-2026).

## License and credit

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit with a link:

> Source: Dolidob (https://dolidob.com), CC BY 4.0. DOI: 10.5281/zenodo.24421615

These figures are estimates for education, not tax advice. Found an error? https://dolidob.com/contact/
