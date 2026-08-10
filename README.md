# 🍽️ Menu Price Merger

<div align="center">

### Offline → Online Menu Price Synchronizer

Merge restaurant **Offline (Dine-in)** and **Online** menu CSVs in seconds while preserving online availability and replacing prices with offline values.

https://atomxharshyt.github.io/dinetoonline/

No installation. No server. No data upload. Everything runs **100% inside your browser**.

---

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Offline](https://img.shields.io/badge/Works%20Offline-Yes-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

# ✨ Features

## 🔄 Smart Menu Merge

- Match items using **Item Name**
- Replace **Online Price** with **Offline Price**
- Preserve **Online Availability**
- Automatically append **Offline-only** items
- Generates a clean final Online-format CSV

---

## 🏷 Optional Suffix Removal

Supports menus where online items contain suffixes like:

```
Paneer Butter Masala [O]
Veg Burger [ONLINE]
```

Simply enter:

```
[O]
```

or

```
[ONLINE]
```

before merging.

---

## 📊 Detailed Statistics

After processing you'll instantly see:

- Offline Items
- Online Items
- Matched Items
- Offline-only Items
- Final Output Rows
- Suffixes Removed

---

## 📄 Download Reports

The application generates:

### ✅ Final Merged Menu

Complete online menu with updated prices.

---

### 🆕 Offline-only Items

Items that exist only in the offline menu.

---

### ⚠ Online Items Without Offline Match

Items whose prices could not be updated because no matching offline item exists.

---

# 🍽 Dine-in Only Processor

Don't have an Online Menu?

No problem.

The built-in processor can clean and prepare a Dine-in menu by:

- Adding **Area Display Name**
- Detecting non-food items
- Marking them as **Available = No**
- Leaving food items unchanged

Perfect for preparing menus before uploading online.

---

# 🚫 Automatic Non-Food Detection

Includes hundreds of built-in keywords including:

- Tissue
- Cutlery
- Packaging
- Parcel Charges
- Decoration Charges
- Alcohol
- Beer
- Wine
- Cigarettes
- Service Charges
- Event Charges

The keyword list is fully editable.

---

# ⚙ Merge Logic

```
Offline Menu
        │
        ▼
Price Source
        │
        ▼
Online Menu
        │
Availability Source
        │
        ▼
Merged Output
```

Rules:

- ✅ Price comes from Offline Menu
- ✅ Availability comes from Online Menu
- ✅ Offline-only items are added
- ✅ Offline-only items become Available = No
- ✅ Output follows Online Menu structure

---

# 📂 Required CSV Columns

## Offline Menu

| Column |
|---------|
| Item Name |
| Price |

---

## Online Menu

| Column |
|---------|
| Item Name |
| Price |
| Available |

---

# 📁 Output Columns

```
Item ID
Category
Item Name
Variation
Online Display Name
Area Display Name
Item Type
Price
Description
Dietary
Available
Goods/Services
```

---

# 🚀 How to Use

## Menu Merge

1. Upload Offline Menu CSV
2. Upload Online Menu CSV
3. (Optional) Enter suffix code
4. Click **Merge Menus**
5. Download results

---

## Dine-in Processor

1. Open **Dine-in Only Processor**
2. Upload Dine-in CSV
3. Edit keyword list (optional)
4. Process
5. Download processed CSV

---

# 🔒 Privacy

Everything happens locally.

- ✅ No uploads
- ✅ No server
- ✅ No tracking
- ✅ No internet required
- ✅ Your data never leaves your computer

---

# 💻 Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- FileReader API
- Blob API

No frameworks.
No dependencies.
No build tools.

---

# 📷 Preview

```
┌───────────────────────────────────────────┐
│          Menu Price Merger                │
├───────────────────────────────────────────┤
│  📂 Offline CSV     🌐 Online CSV         │
│                                           │
│     ⚡ Merge Menus                        │
│                                           │
│  📊 Statistics                            │
│                                           │
│  ✅ Results                              │
│  ⬇ Download Final CSV                    │
└───────────────────────────────────────────┘
```

---

# 🎯 Ideal For

- Restaurants
- Cafés
- Cloud Kitchens
- POS Operators
- Menu Management Teams
- Food Aggregator Operations

---

# ⭐ Highlights

- ⚡ Fast
- 🖥 Runs Offline
- 📄 CSV Based
- 🎨 Modern Glass UI
- 🚀 Zero Installation
- 🔒 Privacy Friendly

---

<div align="center">

### Built for simplifying restaurant menu management.

⭐ If you found this project useful, consider starring the repository.

</div>
