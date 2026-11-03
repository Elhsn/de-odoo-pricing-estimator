# DE Odoo Pricing Estimator

Internal Digital Economics sales tool for estimating Odoo implementation, customization, training, integration and support effort on new projects.

Live page: https://elhsn.github.io/de-odoo-pricing-estimator/

## What it does

- 47 Odoo modules with official icons, grouped (Sales, Finance, Inventory & Manufacturing, HR, Services, Marketing, Productivity), each with editable default hours
- Size factors: users, companies, project complexity
- Customization and integration lines (evidence or assumption marked on each)
- Training hours per module, post go-live support block, optional retainer
- Discount, VAT, USD/EGP display
- Summary with per-section breakdown, print / save as PDF, copy quote summary
- Save named estimates in the browser (localStorage - stays on the device, nothing is sent anywhere)
- English / Arabic

## Notes

- Default hours and factors are working estimates from past DE quotations where available, and assumptions elsewhere. Everything is editable. A client quotation is issued by DE only after management review.
- Odoo licenses, hosting and third-party subscriptions are excluded unless added as a line.
- Single self-contained `index.html`, no build step, no dependencies.
