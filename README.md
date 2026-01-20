# SAESRPG - Custom Vehicle Wraps

Welcome to the official community vehicle wrap repository for **SAESRPG**.

This repository allows players and organisations to upload and manage custom vehicle wraps.

> **ℹ️ Need more info?**
> Detailed documentation and usage guides can be found on the [Wiki](https://github.com/saesrpg/vehicle-wraps/wiki).

## 📂 Which type of wrap are you adding?

Please choose the instruction set below that matches your needs.

| Wrap Type | For Who? | Requirement |
| :--- | :--- | :--- |
| **Donation Wraps** | Individual Players | Requires Donation Points. |
| **Organisation Wraps** | Groups, Gangs, Squads | For official organisations. |

## 👤 Option 1: Donation Wraps (Players)

Wraps for individual users must follow a strict **username** and **sequential number** format.

### 1. Folder Structure
Navigate to: `RPGvehicleWrapAssets/wraps/custom/users/`

1.  Find or create a folder with your **exact username** (e.g., `ronseal`).
2.  Inside your user folder, create a new folder using the next **sequential number**.
    * *Example:* If `001` exists, name the new folder `002`.

**Example Path:**
`RPGvehicleWrapAssets/wraps/custom/users/ronseal/001/`

### 2. Required Files
Inside your numbered folder (`001`), add the following:

* **`wrap.png`** (Required)
    * The image file **must** be strictly named `wrap.png`.
    * Do not use other names.

* **`allowed.txt`** (Optional)
    * Create this file to restrict access.
    * List allowed SAES usernames, one per line.
    * *If omitted, the wrap is public.*

Example (allowed.txt):

```text
    ronseal
    nanobob
    brophy
```

## 🏢 Option 2: Organisation Wraps

Wraps for organisations are stored by organization type (gang, squad, group, etc.).

### 1. Folder Structure
Navigate to: `RPGvehicleWrapAssets/wraps/custom/orgs/`

1.  Open the folder matching your organization type (e.g., `group`, `gang`, `squad`).
2.  You do **not** create a sub-folder here. You simply drop the image file directly into this folder.

**Example Path:**
`RPGvehicleWrapAssets/wraps/custom/orgs/group/`

### 2. Required Files
* **`<orgname>.png`** (Required)
    * The image file should be named after your organization (e.g., `soa.png`, `bope.png`).
    * *Note: Organisation wraps do not use `allowed.txt`.*

## 🚀 How to Submit (Pull Request)

Once you have prepared your files locally, follow these steps to upload them:

1.  **Fork the Repository:** Click the "Fork" button (top-right) to create your own copy.
2.  **Add Your Files:** Create the folders and upload the files as described in Option 1 or Option 2 above.
3.  **Commit:** Save your changes with a descriptive message (e.g., `Added wrap: ronseal/001` or `Added org wrap: soa.png`).
4.  **Open a Pull Request:**
    * Go to the "Pull Requests" tab in the original `SAESRPG/vehicle-wraps` repository.
    * Click **New Pull Request**.
    * Select your fork and submit.

## ✅ General Rules

* **File Format:** All images must be in **.PNG** format.
* **File Naming:**
    * **Users:** Must be `wrap.png`.
    * **Orgs:** Must be `orgname.png`.
* **Content:** Designs must comply with SAESRPG community guidelines.

## ❓ Troubleshooting

If you need help, contact support on Discord: https://saesrpg.uk/discord