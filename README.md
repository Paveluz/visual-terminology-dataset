
# Imagetranslation Visual Terminology Dataset

**Imagetranslation.org** is an open multilingual and multimodal dataset that links domain-specific terminology with annotated illustrations. Each term is assigned a label on an image, translated into multiple languages, and optionally described with a short definition or usage context.

This dataset is designed to help train and evaluate language models, multimodal systems, and educational tools by providing visual grounding for technical concepts.

---

## ✨ Key Features

- Multilingual support (`term_en`, `term_ru`, `term_uz`, `term_cn`, `term_de`, etc.)
- Visual identification using numbered arrows
- Domain categorization (e.g., Mechanical Engineering, Oil and Gas)
- Structured, extendable JSON format
- Designed for integration with real-world educational and AI systems

---

## 📁 Dataset Structure

Each entry in the dataset contains the following fields:

| Field                | Description |
|----------------------|-------------|
| `image_file`         | Name of the image file (e.g., `fig1_milling.png`) |
| `image_caption_en`   | Image caption in English (optional) |
| `image_caption_ru`   | Image caption in Russian (optional) |
| `category`           | Domain or subject area of the image |
| `terms`              | A list of labeled terms shown on the image |

Each term includes:

| Field                | Description |
|----------------------|-------------|
| `label_number`       | The number shown on the image label or arrow |
| `term_*`             | The term in one or more supported languages (e.g., `term_en`, `term_ru`) |
| `context_term_*`     | Short definition or usage context in a specific language |

You may omit any language-specific field (`term_cn`, `context_term_de`, etc.) if it is not yet filled. These fields are expandable and can be added later.

---

## 🛠 Editing and Expanding the Dataset

This dataset can be expanded using the visual interface at [https://imagetranslation.org](https://imagetranslation.org).

Through the interface, you will be able to:

- Upload a clean image (without any labels or text)
- Add arrows and numbers using built-in tools
- Add and edit terms in multiple languages
- Fill in definitions and contexts

🔧 *Note: The site is currently under active development.*  
At the moment, not all fields can be added and JSON export is not yet available.  
However, **core functionality works** — including drawing arrows, numbering, and editing terms.

---

## 🤝 How to Contribute or Collaborate

We welcome collaboration!

If you would like to:
- contribute your language skills,
- help with development or refinement of the platform,
- financially support the project,
- or hire our team to prepare a custom visual dataset for your AI application —

please contact the author directly.

👤 **Author**: Pyak Pavel  
📍 **Location**: Tashkent  
📧 **Email**: admin@imagetranslation.org

---

## 📜 License

This demo dataset is released under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.  
You are free to use, share, and adapt this dataset **for non-commercial purposes** with proper attribution.

🔒 **Commercial use of this dataset or access to the full version is only available upon request.**  
Please contact the author for licensing and collaboration opportunities.

🔗 [CC BY-NC 4.0 License Overview](https://creativecommons.org/licenses/by-nc/4.0/)

