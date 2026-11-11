# 🌊 Hurghada Property — Real Estate & Living Guide in Hurghada

An informational and service project dedicated to buying, renting, and comfortable living in Hurghada, Egypt. This repository contains the static HTML web structure, multi-language support (RU, EN, SR), district guides, and practical lifestyle articles.

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Website Structure & Articles](#-website-structure--articles)
- [Repository Organization](#-repository-organization)
- [Quick Start & Local Setup](#-quick-start--local-setup)
- [Relative Navigation Links](#-relative-navigation-links)
- [Contact Information](#-contact-information)

## 🚀 About the Project

The **Hurghada Property** platform is designed to assist expats, freelancers, investors, and long-term tourists looking to rent, buy property, or relocate to the Red Sea coast.

### Key Highlights:

* **Multilingual Platform:** Complete translation and instant language switching between Russian, English, and Serbian.
* **Hotel vs. Apartment Living:** Economic comparisons, freedom of choice, and long-term stay benefits.
* **Comprehensive City Guides:** District overviews (El Kawsar, Hadaba, Sahl Hasheesh, El Gouna, etc.), infrastructure, transport, internet, and daily utilities.

## 📚 Website Structure & Articles

The website features an interactive landing page (`index.html`) with smooth scrolling sections and a dynamic language switcher, linking to 6 core informative articles across three language directories (`articles/Ru/`, `articles/Eng/`, `articles/Sr/`):

### Core Landing Sections (`index.html`):
1. **Hero Section:** Overview of Hurghada real estate with quick navigation.
2. **Buy (`#buy`):** Information on purchasing apartments and flats.
3. **Rent (`#rent`):** Short-term and long-term apartment rental offers.
4. **Useful Information (`#info`):** Grid of 6 detailed guide articles.

---

### Featured Articles (`articles/Eng/`):

1. **`article1.html` — Egypt as people imagine it, and Egypt as people live in it now**
   * *Overview:* Breaking stereotypes about Egypt, highlighting city infrastructure, Amazon delivery, Spinneys, IKEA, Uber, and local lifestyle.

2. **`article2.html` — Complete Guide to the Internet in Hurghada**
   * *Overview:* Mobile operators (Vodafone, Etisalat, Orange, WE), SIM card registration, WE home broadband connection, and the 90-day IMEI tax rule for foreign phones.

3. **`article3.html` — Complete Guide to Hurghada Neighborhoods**
   * *Overview:* Detailed analysis of 8 districts (El Kawsar, Sheraton, Hadaba, Madares, Dahar, El Ahyaa, Sahl Hasheesh, El Gouna), including prices per sq. m, beach access, cleanliness, and security rankings.

4. **`article4.html` — All-Inclusive Hotel vs. Owning/Renting Your Own Apartment**
   * *Overview:* Financial savings up to 70% for month-plus stays, routine independence, food quality, and living space comparisons.

5. **`article5.html` — How to Avoid Real Estate Scams in Hurghada**
   * *Overview:* Safety protocols when renting or buying, understanding Tawkils, Green Contracts, unfinished off-plan risks, municipal water/electricity meters, and maintenance fees.

6. **`article6.html` — Living in Hurghada Outside Hotels**
   * *Overview:* Essential daily life guide covering shopping malls (Senzo Mall, Hurghada City Center), Duty Free, ride-hailing apps (Uber, InDrive), intercity Go Bus, Talabat delivery, medical services in El Kawsar, and emergency contacts.

## 📂 Repository Organization

```text
hurghada-property/
├── README.md                   # Repository documentation
├── index.html                  # Main multilingual landing page
├── images/                     # Graphic assets and article covers
│   ├── hero.png
│   ├── buy.png
│   ├── rent.png
│   ├── article-1.jpg
│   ├── article-2.jpg
│   ├── article-3.jpg
│   ├── article-4.jpg
│   ├── article-5.jpg
│   └── article-6.jpg
└── articles/                   # Language-specific article directories
    ├── Ru/                     # Russian versions (article1.html ... article6.html)
    ├── Eng/                    # English versions (article1.html ... article6.html)
    └── Sr/                     # Serbian versions (article1.html ... article6.html)
```

## 🛠️ Quick Start & Local Setup

The project is built using pure HTML5, CSS3, and lightweight vanilla JavaScript for dynamic i18n translation. No build steps or node packages are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hurghada-property.git
   ```

2. **Navigate into the directory:**
   ```bash
   cd hurghada-property
   ```

3. **Open in browser:**
   * Open `index.html` directly in any web browser or run it using VS Code's **Live Server** extension.

## 🔗 Relative Navigation Links

To maintain correct path routing across different subdirectories, relative link formatting is applied:

* From `index.html` to an English article: `articles/Eng/article3.html`
* Back link from any article to the main landing page: `../../index.html#info`
* Image paths from articles: `../../images/article-3.jpg`

## 📞 Contact Information

For real estate inquiries, rental options, or apartment selection in Hurghada:

* **Email:** [egypt26@proton.me](mailto:egypt26@proton.me)
* **Telegram:** [@hurgada_realestate](https://t.me/hurgada_realestate)

© 2026 **Hurghada Property**. All rights reserved.