# 🧩 Shopify Marketplace Links Snippet

A Shopify Liquid snippet that dynamically displays product prices and links from multiple marketplaces — **Trendyol** and **Hepsiburada**.  
This code allows you to show marketplace prices and links directly on your Shopify product pages using **metafields**.

---

## 💡 Features
- Shows price and link info for **Trendyol** and **Hepsiburada**.
- Uses **Shopify metafields** for easy, flexible data management.
- Works in any theme without external scripts.
- Responsive and minimal design.

---

## ⚙️ How to Use

1. Go to your **Shopify Admin → Online Store → Themes → Edit code**
2. Under **Snippets**, click **Add a new snippet** and name it:  
   `marketplace-links.liquid`
3. Paste the code below into the file:
{% render 'marketplace-links' %}


Make sure you have the following metafields created under your Product metafields:

| Namespace | Key               | Type   | Example Value                                                       |
| --------- | ----------------- | ------ | ------------------------------------------------------------------- |
| custom    | trendyol_link     | URL    | [https://www.trendyol.com/urun/](https://www.trendyol.com/urun/)... |
| custom    | trendyol_fiyat    | Number | 499.90                                                              |
| custom    | hepsiburada_link  | URL    | [https://www.hepsiburada.com/](https://www.hepsiburada.com/)...     |
| custom    | hepsiburada_fiyat | Number | 505.00                                                              |

