# RefundThePeople.org — Track How Your State Spends Your Income

This project empowers citizens by showing detailed breakdowns of tax money collected and how it is spent (or wasted) by their state government.

---

## What It Does

- Displays **total taxes collected** by each U.S. state (using real IRS 2023 data).
- Shows approximate allocations to:
  - Roads
  - Schools
  - Public Safety
  - Waste / Slush Funds
  - Missing / Unaccounted Funds
- Provides **source links** for transparency and further research.

---

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Select your state from the dropdown.
4. Click **Reveal** to see the financial breakdown.
5. Click source links for detailed info.

---

## Files

- `index.html`: Frontend user interface to view data.
- `states.json`: Data file containing tax and spending info for all 50 states.

---

## How to Add or Update Data

- Edit `states.json` to update numbers or add new fields.
- Ensure you keep the same JSON structure for compatibility.

---

## How to Deploy

- Host on any static web server (GitHub Pages, Netlify, Vercel, etc.).
- Ensure both `index.html` and `states.json` are in the root directory or adjust fetch paths accordingly.

---

## Future Plans

- Add county- and zip-code-level data.
- Integrate live data fetching from government APIs.
- Provide downloadable reports for personal or community use.

---

## Contributing

Feel free to open issues or submit pull requests for:

- Adding accurate data
- UI improvements
- Bug fixes
- Automation scripts for data fetching

---

## Sources

- IRS Tax Data: [https://www.irs.gov/statistics](https://www.irs.gov/statistics)  
- USASpending: [https://www.usaspending.gov](https://www.usaspending.gov)  
- Government Accountability Office: [https://www.gao.gov](https://www.gao.gov)  
- Oversight.gov: [https://www.oversight.gov](https://www.oversight.gov)  

---

## License

MIT License © 2025 RefundThePeople.org  
