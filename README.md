# 🌍 World Geo Data — Full Country, State, City & Currency Dataset

This repository provides an overview of the **World Geo Data** digital product — a ready-to-use dataset bundle containing detailed geographic and administrative information, including continents, countries, states, cities, and currencies.

This dataset includes structured lists of:
- Countries
- States/Provinces
- Cities
- Continents
- Currency

Each dataset is provided in:
- MySQL (`.sql`)
- CSV format
- JSON data format
- SVG Flag icons for all Countries
- Sample SQL queries

✅ Ready to import into any MySQL or PostgreSQL DB  
📦 Useful for developers, SaaS founders, UI designers, data analysts & educators.

---

## 📜 License

Licensed under MIT — use it freely in personal and commercial projects.

---

## ✨ Use Cases

- Create country/state dropdowns
- Add region filters to your SaaS
- Power location-based dashboards
- Academic & data analysis projects
- You can make your own scenarios and use cases...

  <hr>
## 📦 What's Included?
<pre>
├───1. Continents
│       continents.csv
│       continents.json
│       continents.sql
│       LICENSE.md
│
├───2. Countries
│   │   countries.csv
│   │   countries.json
│   │   countries.sql
│   │   LICENSE.md
│   │   Readme-svg-country-flag-icons.txt
│   │
│   └───svg-country-flag-icons
│     
│
├───3. States
│       LICENSE.md
│       states-with-countryid-mapping.csv
│       states.csv
│       states.json
│       states.sql
│
├───4. Cities
│       cities-with-state-and-country-mapping.csv
│       cities.csv
│       cities.json
│       cities.sql
│       LICENSE.md
│
└───5. Currencies
        currencies.sql
        currency.csv
        currency.json
        LICENSE.md
</pre>


Each file is cleanly structured and ready for integration into apps, databases, analytics platforms, or localization projects.

---

## 🛒 Buy Now

Get instant access to the full dataset:

👉 [**Buy on Gumroad**](https://digitalworkerbees.gumroad.com/l/world-data-bundle)  

---

## ✍️ Read the Full Article

Learn more about how and why this dataset was built, including use cases and technical decisions:

📖 [**Read the Medium article**](https://your-medium-article-url-here)  

---

## 📂 File Format Support

All major formats are included:

- `.csv` — for spreadsheets and tabular data tools
- `.json` — for developers and APIs
- `.sql` — for direct database import (MySQL, PostgreSQL compatible)

---
## ♻️ How to Use SVG Country flag icons using css approach?

Refer to live demo on [**Stackblitz**](https://stackblitz.com/edit/flag-icons-stackblitz-demo-add-country-flag-icons)

For more instruction on how to setup and use svg using css class, Refer below articles:

[1] [**Best Way to Add Country Flag Icons in Angular Using css approach (2025)**](https://medium.com/beingcoders/best-way-to-add-country-flags-icon-in-angular-6b593a25d0f3) <br/>
Discover the most efficient and modern methods to integrate country flag icons into your Angular app in 2025 with this easy-to-follow guide.

[2] [**Best Way To Add Country Flag Icons In Angular**](https://www.9mood.com/add-country-flag-icons-in-angular/) <br/>
Flag Icons Stackblitz Example in Angular, A powerful approach to render country flag icons in your web apps.

---
## 🫰Sample Queries:

**For continents table:**
<pre>
CREATE TABLE `continent_master` (
  `id` int NOT NULL AUTO_INCREMENT,
  `code` varchar(3) NOT NULL,
  `name` varchar(150) NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `code` (`code`,`name`)
);
</pre>

**Insert Queries:**

<pre>
INSERT INTO `continent_master` VALUES (1,'AF','AFRICA');
</pre>


---

## 🔐 Licensing

Each folder includes a separate `LICENSE.md` file detailing usage rights. Please review them before using in commercial or open-source projects. Licensed under MIT, it can be used freely in personal and commercial projects.

---

## 🙌 Contribution

This repo is for documentation purposes only. If you have suggestions or questions about the dataset, feel free to reach out via [email](mailto:admin@digitalworkerbees.com).

---

## ⭐ Why Use This?

- ✅ Clean, consistent, and standardized
- 🌐 Global coverage
- 🛠️ Ready for production
- 📊 Ideal for developers, UI designers, analysts, and entrepreneurs

---

Thanks for visiting — don't forget to ⭐️ this repo if you found it helpful!
