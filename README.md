# KnowYourLabel 🏷️

**KnowYourLabel** is an open-source, lightweight web application designed to help consumers decode packaged product labels. By scanning a barcode or pasting an ingredient list, the app retrieves product details and leverages AI to break down the functional role of each ingredient in the product alongside its potential impact on human health.

---

## ✨ Features

* **In-Browser Barcode Scanning:** Uses local image processing via ZXing to read 1D/2D product barcodes directly in the browser.
* **Database Integration:** Automatically queries the open-source **Open Food Facts API** to fetch product names and verified ingredient lists.
* **AI-Powered Ingredient Analysis:** Connects to the **Google Gemini API** to analyze complex chemical names, explaining:
  * **Functional Role:** (e.g., Emulsifier, Preservative, Texturizer, Flavor Enhancer)
  * **Human Health Impact:** Benefits, allergen considerations, and daily consumption guidance.
* **Manual Fallback:** Allows users to paste ingredient lists directly for custom formulations or unindexed products.
* **Zero Infrastructure:** Built using pure client-side HTML, CSS (Tailwind), and JavaScript—ready to host for free on GitHub Pages.

---

## 🚀 Live Demo

Access the live web application here:  
👉 **[https://anuvrat03.github.io/KnowYourLabel](https://anuvrat03.github.io/KnowYourLabel)**

---

## 🛠️ Tech Stack & Open-Source Libraries

* **Frontend:** HTML5, JavaScript (ES6+), [Tailwind CSS](https://tailwindcss.com/)
* **Barcode Detection:** [ZXing JS](https://github.com/zxing-js/library)
* **Product Data:** [Open Food Facts API](https://world.openfoodfacts.org/)
* **AI Engine:** [Google Gemini API](https://aistudio.google.com/)
* **Hosting:** GitHub Pages

---

## 📋 How to Use

1. **Obtain a Free Gemini API Key:**
   * Visit [Google AI Studio](https://aistudio.google.com/) and generate a free API key.
2. **Launch the App:**
   * Open the live site URL or open `index.html` locally in any web browser.
3. **Analyze a Product:**
   * Enter your Gemini API key in the top field.
   * Upload an image containing a product barcode **OR** paste an ingredient list into the text box.
   * Click **Analyze Product & Ingredients** to view the generated health report.

---

## 📂 Project Structure

```text
KnowYourLabel/
├── index.html     # Complete single-file application (UI, logic, API calls)
└── README.md      # Project documentation
