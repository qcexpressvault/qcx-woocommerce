# QC Express for WooCommerce

> 🚚 Seamless integration of [QC Express](https://qcexpress.co) shipping services with WooCommerce.  
> Developed and maintained by [Eriyo Digital](https://eriyodigital.com) — building Africa-focused logistics and fintech solutions.

---

## ✨ Features

- **Real-time Shipping Rates** — live QC Express quotes shown at checkout
- **Automatic Booking Creation** — shipments created when orders are processed/completed
- **Insurance Options** — let customers choose insurance or enforce it
- **Document & Parcel Support** — handle both document and non-document shipments
- **Custom Tracking Pages** — provide shipment tracking directly on your site
- **Admin Tools** — create/cancel bookings and download labels in WooCommerce admin
- **Detailed Logging** — track API calls for debugging and support
- **Multi-currency Support** — works with your WooCommerce store currency
- **Shipping Zones** — configure QC Express per zone

---

## ⚙️ Installation

1. [Download the latest release](https://github.com/qcexpressvault/qcx-woocommerce/releases).
2. In WordPress, go to **Plugins → Add New → Upload Plugin**.
3. Upload the `qcx-woocommerce.zip` file and activate.
4. In WooCommerce → Settings → **QC Express**, enter your API **Client ID** and **Token**.
5. Add **QC Express** as a shipping method under WooCommerce → Shipping Zones.

---

## 🔧 Configuration

- **API Setup**: Input your QC Express API credentials from the developer portal.
- **Business Details**: Set your sender information, origin address, and default package dimensions.
- **Shipping Zones**: Add QC Express as a shipping method where you want it enabled.
- **Insurance**: Decide whether insurance is optional or mandatory.
- **Markup**: Add a fixed or percentage markup to shipping quotes (optional).

---

## 📸 Screenshots

1. Settings page with API configuration
2. Shipping method setup in zones
3. Checkout showing QC Express shipping options
4. Order admin with booking controls and tracking number
5. Tracking page for customers

---

## ❓ FAQ

**Do I need a QC Express business account?**  
Yes. You’ll need a QC Express account and valid API credentials.

**Can I customize rates?**  
Yes — you can apply fixed or percentage markup in settings.

**Does it work with variable products?**  
Yes — weight and dimensions are calculated for all items in the cart.

**Is the plugin free?**  
Yes, but you’ll incur shipping costs from QC Express.

**How do I add commodity codes for exports?**  
Add a custom field `commodity_code` with the HS Code to each product (required for customs clearance).

---

## 📦 Requirements

- WooCommerce 3.0 or higher
- WordPress 5.0 or higher
- PHP 7.4 or higher
- QC Express account + API credentials

---

## 🔒 Privacy

This plugin sends shipping data (addresses, weights, declared values) to QC Express servers for rate calculation and booking creation.  
See [QC Express’s privacy policy](https://qcexpress.co/privacy) for details.

---

## 🧑‍💻 About Eriyo Digital

This plugin is proudly built and maintained by **[Eriyo Digital](https://eriyodigital.com)** — a software development and consultancy company delivering **logistics, fintech, and e-commerce solutions for African businesses**.

- 🌍 African-first innovation
- 🚀 Custom WooCommerce and API integrations
- 💼 Software consultancy for SMEs and enterprises

👉 Need custom WooCommerce development, logistics APIs, or fintech integrations?  
**[Contact us](mailto:consultancy@eriyodigital.com)**

---

## 📄 License

This plugin is open-sourced software licensed under the [GPL v2 or later](https://www.gnu.org/licenses/gpl-2.0.html).
