# EasyAI

**EasyAI** is a lightweight AI launcher for fast and easy setup. It includes optional **Training Extra SPs**, which extend the AI’s knowledge with structured data and reference information, helping it respond accurately, follow rules, and reduce hallucinations.

---

## Features

* **Easy setup** – run `Launch.bat`.
* **Model selection** – pick any model in `EasyAI/Models/...`.
* **Training Extra SPs** – optional prompts to improve accuracy and factual consistency.
* **Lightweight and fast** – minimal dependencies, works on standard Windows PCs.

---

## Training Extra SPs

Structured facts and rules to enhance AI responses.

### Versioning

* **Base Versions** – Full, uncompressed content (V1, V2, etc.). Reference only.
* **SC (Short Code)** – Frequent terms replaced with short codes. Moderate compression.

  * Example: `Intel Core i9-13900 → INT i9-13900`
* **TM (Token Mapping)** – Terms and structures mapped to tokens for maximum compression.

  * Example: `AMD Ryzen 7 5800X3D → R7-5800X3D`

> Versions without SC or TM are base/reference only.

---

## Usage

1. Place your model in `EasyAI/Models/...`.
2. Run `EasyAI_Launcher.bat`.
3. Select a model.
4. Use **Training Extra SPs** if desired.
5. Start Chatting.
