# Business Scout

Finds local businesses on Google Maps and collects their contact details into a spreadsheet.

Live: https://bxzex.github.io/leads-scraper/

Search for a kind of business in a city. It grabs the name, phone, address, rating and website, then visits each website looking for an email, Instagram and Facebook. Export the lot to CSV.

It runs Playwright on your own machine:

```bash
npm install
npx playwright install chromium
npm run dev
```

Then open localhost:3000. Please use it within Google's terms and local rules on contacting businesses.

Made by [bxzex](https://bxzex.com).
