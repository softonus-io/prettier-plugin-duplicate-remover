# 🚀 Prettier Plugin: Duplicate Remover

## 🚀 About
Prettier plugin that removes duplicate class names from `className` (JSX/TSX/React), `class` (HTML, Angular, Vue), and similar attributes in your code, ensuring clean and consistent class usage.

Supports the following:
- React (JSX/TSX) – `className`
- Angular – `class`
- Vue – `class`
- HTML – `class`
  
By eliminating duplicate class names, this plugin helps maintain cleaner, more efficient markup.

## 🗂 Install

You can install the plugin using any of the following package managers:

### Bun:

```bash
bun add -D @softonus/prettier-plugin-duplicate-remover
```

### Yarn:

```bash
yarn add -D @softonus/prettier-plugin-duplicate-remover
```

### Npm:

```bash
npm install --save-dev @softonus/prettier-plugin-duplicate-remover
```

## 🔨 Usage

Once installed, you need to add this plugin to your Prettier configuration file (`.prettierrc`).

### Steps:

1. **Create a `.prettierrc` file** in your project's root directory (if you don't have one).
2. **Add the plugin configuration** to your `.prettierrc` file:

```json
{
  "plugins": ["@softonus/prettier-plugin-duplicate-remover"]
}
```

This will enable the plugin, and Prettier will automatically remove duplicate class names during formatting.

### Example:

Before formatting:

```html
<div class="btn btn btn-primary btn btn-large">Button</div>
```

After formatting:

```html
<div class="btn btn-primary btn-large">Button</div>
```

## 📝 Features

- **React (JSX/TSX)**: Removes duplicate `className` attributes.
- **Angular, Vue, HTML**: Removes duplicate `class` attributes.
- **Ensures clean and consistent markup**: Prevents unnecessary repetition of class names.

## 🏗️ Supported Languages

- **React** (`.jsx`, `.tsx`) – Handles `className`
- **Vue** (`.vue`) – Handles `class`
- **Angular** (`.html`, `.ts`) – Handles `class`
- **HTML** (`.html`) – Handles `class`

## 🏆 Contributing

If you’d like to contribute to this project, feel free to fork it, make changes, and open a pull request. Your contributions are always welcome!

## 📨 Contact

For any questions or issues, please contact me at:  
**ebo@softonus.com**

---

### 💡 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
