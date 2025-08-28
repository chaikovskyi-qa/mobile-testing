# 🧠 Observations – Adaptive UX Mobile Checks (26.08.2025)

## ✅ Observation 1: Clean structure and intuitive mobile UX

- The mobile layout is logically structured: header, categories, and CTAs are placed where expected.
- Navigation elements like filters, forms, and buttons are intuitive and respond well to taps.

**Positive note**:
- Minimal UX friction — the user easily completes scenarios like login, search, and add to cart.
- Visual hierarchy is preserved across breakpoints (375px, 768px), ensuring consistent readability.

---

## 🔍 Observation 2: Missing Retina (DPR) image support

- Several images do not scale correctly on high-DPI (Retina) screens:
  - `.png` used without `srcset`, and `intrinsic size` is not sufficient.
  - Example: image rendered at `398×492` with intrinsic `768×492` does not meet the requirement `Rendered × DPR ≤ Intrinsic`.

**Recommendation**:
- Use `srcset` or `.svg` for responsive image delivery based on device DPR.
- Ensure all visual assets meet clarity standards for DPR ≥ 2.
