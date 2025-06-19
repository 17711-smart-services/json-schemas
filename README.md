# 📐 17711 Smart Services — JSON Schemas 

**φ Open and composable data formats for smart services, people, media, and processes.**

This repository contains JSON Schema definitions maintained by **17711 Smart Services** and designed to support interoperable, verifiable, and semantic data structures across multiple domains, including:


-   🏷️ Universal identifiers via `φrn` (Φ Resource Name)
-   🧾 Standardized metadata for various resources: documents, media, APIs, batchs, processes...
-   🏢 Organization, people & institutions
-   📚 Education, certifications & projects
-   🧠 Skills, hobbies, soft/hard categorization
-   📄 CVs & profiles
-   (...)

---

## 🗒️ Table of Contents

1.  [Available Schemas](#-available-schemas)
2.  [Get Started](#-get-started)
3.  [Usage](#-usage)
4.  [Contributing](#-contributing)
5.  [History](#-history)
6.  [Credits](#-credits)
7.  [License](#-license)

---

## 🔗 Available Schemas

| Schema | $id |
| :------- | :-------------------------------------------------------------------------------------- | 
| `[ΦRN Schema]`(./urn.shema.json) | [`https://schemas.17711.eu/schema/urn.schema.json`](https://schemas.17711.eu/schema/urn.schema.json)

*All schemas are fully JSON Schema Draft 2020-12 compliant and versioned.*

---

## 🚀 Get Started

To begin using these schemas, you'll primarily interact with the **`urn.schema.json`** which defines the fundamental structure for Universal Resource Names (URNs) used across our ecosystem. This schema is key for unique identification of resources.

---

## 📝 Usage

You can reference any schema directly via its `$id`. For instance, to use the `urn.schema.json`:

```json
{
  "$schema": "[https://json-schema.org/draft/2020-12/schema](https://json-schema.org/draft/2020-12/schema)",
  "$ref": "[https://schemas.17711.eu/schema/urn.schema.json](https://schemas.17711.eu/schema/urn.schema.json)"
}
```

## 🤝 Contributing

We welcome contributions to improve and expand these JSON Schema definitions. If you'd like to contribute, please follow these guidelines:

1.  **Fork the repository**.
2.  **Create a new branch** for your feature or bug fix.
3.  **Ensure your changes adhere to JSON Schema Draft 2020-12 standards**.
4.  **Write clear commit messages**.
5.  **Submit a pull request** with a detailed description of your changes.

---

## 🗓️ History

For a comprehensive overview of changes, new features, and bug fixes across different versions, please refer to the **[CHANGELOG](CHANGELOG.md)** file.

---

## 🙏 Credits

These schemas are maintained by **🐚 [17711 Smart Services](https://17711.eu/)**.

---

# 📄 License — CC BY 4.0

> 
> This work is licensed under the **Creative Commons Attribution 4.0 International License**.
> 
> You are free to:
> 
> - ✅ **Share** — copy and redistribute the material in any medium or format  
> - ✅ **Adapt** — remix, transform, and build upon the material for any purpose, even commercially
> 
> Under the following terms:
> 
> - **Attribution** — You must give **appropriate credit**, provide a link to the license, and indicate if changes were made.  
  You may do so in any reasonable manner, but **not in any way that suggests the licensor endorses you or your use**.
> 
> > Proper attribution should include a mention of **🐚 17711 Smart Services**  
> > and a link to the source: [https://17711.eu](https://17711.eu)
> 
> For the full license text, see:  
> 👉 [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
> 
