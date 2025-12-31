# EasyAI

**EasyAI** is a lightweight AI launcher for fast and easy setup. It includes optional **Training Extra SPs**, which enhance any AI model with structured data, rules, and reference information. These SPs help the AI respond accurately, follow rules, and reduce hallucinations—**they work with any AI launcher and any AI model**.

---

## Features

* **Easy setup** – run `EasyAI_Launcher.bat`.
* **Model selection** – choose any model in `EasyAI/Models/...`.
* **Training Extra SPs** – optional prompts that improve factual accuracy and consistency for any AI model.
* **Universal compatibility** – works with any AI model.
* **Lightweight and fast** – minimal dependencies, runs on standard Windows PCs.

---

## Training Extra SPs

Structured facts and rules to enhance AI responses. Designed to work with **any AI model or launcher**, not limited to EasyAI.

### Versioning

* **Base Versions** – Full, uncompressed content (V1, V2, etc.). Reference only.
* **SC (Short Code)** – Frequently used terms replaced with short codes. Moderate compression.

  * Example: `Intel Core i9-13900 → INT i9-13900`
* **TM (Token Mapping)** – Terms and structures mapped to tokens for maximum compression.

  * Example: `AMD Ryzen 7 5800X3D → R7-5800X3D`

> Versions without SC or TM are base/reference only.

---

## Usage

1. Place your AI model in `EasyAI/Models/...`.
2. Run `EasyAI_Launcher.bat`.
3. Select a model.
4. Use **Training Extra SPs** if desired (works with any model).
5. Start chatting.

---

## Notes

* **Training Extra SPs** are compatible with any AI launcher or model.
* Designed for **Windows 10+**, but the SPs can be integrated into other platforms if supported.
