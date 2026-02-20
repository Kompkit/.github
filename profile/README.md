# 🧩 KompKit

**Cross-platform utility kit for Web, Android & Flutter — lightweight, minimal, and open-source.**

---

### 🚀 What is KompKit?

KompKit is an open-source utility library designed for teams building across multiple platforms simultaneously.

It provides the same utility functions — with the same names, the same defaults, and the same behavioral semantics — across **TypeScript (Web/Node)**, **Kotlin (Android/JVM)**, and **Dart (Flutter)**, all managed within a clean **monorepo architecture**.

You learn the API once. You use it everywhere.

---

### 🧠 Current Status

**Version:** `v0.2.0-alpha.0`  
**Stage:** 🧪 Alpha — APIs may change before stable release. Pin to exact versions in production.  
**Branches:**
- `release` → stable versions
- `develop` → active development

**Published packages:**
- [`kompkit-core`](https://www.npmjs.com/package/kompkit-core) — npm (TypeScript/Web)
- [`kompkit_core`](https://pub.dev/packages/kompkit_core) — pub.dev (Dart/Flutter)
- Android/Kotlin — not yet published to Maven; use local project reference

---

### 🗂️ Repositories

- [**kompkit**](https://github.com/Kompkit/kompkit) — main monorepo (Web, Android & Flutter modules)

> More repositories will be added as the project grows toward 1.0.

---

### ⚡ What's Inside

| Utility | Description |
|---|---|
| [debounce](cci:1://file:///Users/ivan/Desktop/IvanDev/kompkit/kompkit/packages/core/web/src/debounce.ts:10:0-45:1) | Delay function execution with [cancel()](cci:1://file:///Users/ivan/Desktop/IvanDev/kompkit/kompkit/packages/core/web/src/debounce.ts:37:2-42:4) support |
| [isEmail](cci:1://file:///Users/ivan/Desktop/IvanDev/kompkit/kompkit/packages/core/android/src/main/kotlin/com/kompkit/core/Validate.kt:7:0-20:68) | Basic email format validation |
| [formatCurrency](cci:1://file:///Users/ivan/Desktop/IvanDev/kompkit/kompkit/packages/core/flutter/lib/src/format.dart:2:0-45:1) | Localized currency formatting (BCP 47) |

All utilities are implemented natively per platform — no shared runtime, no transpilation.

---

### 📘 Documentation

Visit the [**docs folder**](https://github.com/Kompkit/kompkit/tree/release/docs) for:
- Architecture & API parity contract
- CI setup & troubleshooting
- Platform-specific guides (Web, Android, Flutter)
- Contributing guide & changelog

---

### 🤝 Contributing

We're in early alpha and welcome feedback, bug reports, and contributions.  
Check out our [Contributing Guide](https://github.com/Kompkit/kompkit/blob/release/docs/CONTRIBUTING.md) to get started.

---

### 🧩 Maintainer

**Iván Méndez**  
Software Developer  
📧 kompkit@modulumstudio.com

---

### 🌟 Support & Feedback

If you find KompKit useful, consider giving the repo a ⭐  
Early testing, feedback, and ideas are very welcome — the API is still being shaped before 1.0.
