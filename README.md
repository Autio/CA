# Cancer Advocate Research Database

This repository contains the research database for Cancer Advocate - a personal medical literature advocate for pancreatic cancer patients.

## 🌐 Live Web Page

**View the interactive research database:**  
👉 **https://autio.github.io/CA/**

The web page shows:
- 📊 Statistics (total items, trials, publications, repurposed medications)
- 🔍 Searchable interface
- 🏷️ Filter by category (trials, publications, repurposed)
- 📋 Click any item to view on ClinicalTrials.gov or PubMed

## 📁 Repository Contents

- `known_items.json` - The full research database (automatically updated every 7 days)
- `index.html` - The web page source code (used by GitHub Pages)

## 🔄 Automatic Updates

This repository is automatically updated by the Cancer Advocate workflow:
- New clinical trials and publications are added every 7 days
- The web page at https://autio.github.io/CA/ stays current automatically

## 📧 Email Reports

Cancer Advocate sends weekly email reports with:
- New research findings
- Repurposed medications and supplements
- Actionable insights ("Key Takeaways")

## 🛠️ Setup

To enable the web page at https://autio.github.io/CA/:

1. Go to: https://github.com/Autio/CA/settings/pages
2. Under "Source", select: **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Click "Save"
5. Wait ~5 minutes for deployment

## 📖 Learn More

Cancer Advocate is an open-source project that helps pancreatic cancer patients stay informed about:
- Clinical trials matching their molecular profile
- New publications on their specific mutations (KRAS G12D, BRCA2)
- Repurposed medications being studied for pancreatic cancer

---

**Repository owner:** Autio  
**Contact:** mikael.upbeam@gmail.com
