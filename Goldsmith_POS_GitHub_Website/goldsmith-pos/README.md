# Goldsmith POS Website

## Publish on GitHub Pages
1. Create a GitHub repository named `goldsmith-pos`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. Open the URL shown in Pages settings after the site publishes.

## Included
- POS cart and checkout, discounts, cash tender validation, receipt printing
- Shop logo upload, colors, business details and receipt footer customization
- Jewelry inventory with gold weight, karat, costs, selling price and low-stock warning
- Supplier purchases increase stock; sales reduce stock for non-service items
- Customer register
- Custom orders with gold weight/purity, gold cost per gram, stones, materials, labor, charges, deposits and balance
- Service/repair jobs
- Separate payments and deposits register, including refunds
- Expenses, daily/monthly/all-time reporting, CSV export and JSON backup/restore

## Important limitations
- Data is stored in the browser's local storage on that device/browser. GitHub Pages does not sync records between computers or provide user accounts/database.
- Export backups regularly. For multi-device or multi-user access, add a database and authentication backend.
- Card/e-wallet payment methods are recorded only; no actual payment is processed.
- Gold prices per gram are manually entered; there is no live price feed.
- Test calculations, inventory and receipt output with sample data before using for real transactions. Review tax and receipt requirements locally.
