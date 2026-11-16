# Second Life Ledger

**Problem:** Turning everyday waste into a valuable resource.
**Idea:** A site-agnostic platform (college, household, restaurant, apartment, office, shop) that routes each kind of waste to the highest-value use its *local* buyers allow, and shows what is lost when a buyer type is missing.

## Live demo
Enable GitHub Pages (Settings > Pages > Deploy from branch > main / root) and open the published URL. It is a single static `index.html`, no build step, no backend.

## What it does
1. **Log waste** (type or pick a category, enter kg).
2. **Value ladder:** each waste has ranked uses (e.g. food: donate > animal feed > compost > bin). The app picks the best use for which the campus actually has a buyer.
3. **Money left on the table:** shows which missing buyer type would unlock a higher rung, and how much extra value that adds.
4. **Circular credits:** CO2e avoided is converted to a comparable score across campuses.
5. **Campus network:** any college can join with its own currency, prices and buyers. Leaderboard across campuses.
6."right this one model  if u guys watching this support me i will excute this soon "

## Works for any site
Sites are data, not code: type, name, currency symbol, per-kg prices, and a buyer directory. Ten sample sites are preloaded: Rathinam College (RGU) and its hostel mess, colleges in the USA and Kenya, two households, an apartment complex, a restaurant, an IT office and a kirana shop.

## Limits (honest)
- Prices, buyers and CO2e factors are **illustrative sample data**; replace them with local dealer quotes.
- Category guessing is keyword-based, not AI vision.
- Data is stored in the browser (localStorage). A shared backend is the next step.

## Run locally
Open `index.html` in a browser.
