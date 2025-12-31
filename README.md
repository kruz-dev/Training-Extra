# Training Extra (SPs)

## Purpose

The **Training Extra** project contains system prompts designed to extend the AI’s knowledge and rules with structured data, metadata, and reference information. These SPs help the AI respond accurately, follow rules, and reduce hallucinations.

---

## Versioning

### Base Versions

* Examples: **V1, V2, etc.**
* Contain the **full, uncompressed content**.
* Serve as reference versions.

### Optimized Versions

1. **SC (Short Code)**

   * Frequently used terms are replaced with **short codes**.
   * Reduces size moderately.
   * Retains full information.
   * Example: `Intel Core i9-13900 → INT i9-13900`
   * **Compression:** Moderate.

2. **TM (Token Mapping)**

   * Terms, structures, and entities are **mapped to tokens**.
   * Achieves **maximum compression** while keeping all explicit data intact.
   * Example: `AMD Ryzen 7 5800X3D → R7-5800X3D`
   * **Compression:** Strongest currently.

> **Note:** Versions without SC or TM are just base/reference versions.
