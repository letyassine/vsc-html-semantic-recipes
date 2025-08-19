# HTML Semantic Recipes

> Semantic HTML markup patterns for common UI components that work across all frameworks.

![alt text](https://i.postimg.cc/90cpYQ4T/preview.gif "Snippets Preview")

## Overview

HTML Semantic Recipes provides carefully crafted HTML snippets that focus on proper semantic structure and accessibility. Instead of focusing on visual styling, these snippets give you the right HTML foundation that can be styled with your own CSS.

## Features

- Framework-agnostic patterns that automatically adapt to HTML, React, Vue, Angular, and Svelte
- Semantic HTML5 elements used appropriately
- ARIA attributes included where necessary
- Clean, maintainable code patterns

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "HTML Semantic Recipes"
4. Click Install

## Available Snippets

| Prefix                  | Description                                     |
| ----------------------- | ----------------------------------------------- |
| `breadcrumbs`           | Navigation breadcrumbs structure                |
| `card`                  | Card component with header, content, and footer |
| `cardlist`              | Collection of card components                   |
| `checkboxlist`          | Checkbox list with fieldset and legend          |
| `datalist`              | Definition list for key-value data              |
| `formbasic`             | Basic form with standard fields                 |
| `formvalidation`        | Form with inline validation messages            |
| `formvalidationsummary` | Form with validation summary section            |
| `login`                 | Login form with username and password           |
| `nav`                   | Navigation menu structure                       |
| `accordion`             | Expandable accordion sections                   |

## Framework Support

The extension automatically provides the appropriate syntax based on the file type:

### HTML

- Standard HTML5 semantic markup

### React (.jsx/.tsx)

- Uses `className` instead of `class`
- Uses `htmlFor` instead of `for` in labels
- Self-closing tags for inputs

### Angular

- Uses Angular-specific directives
- Angular template binding syntax
- Form validation states

### Vue

- Vue-specific attribute binding
- Vue directives
- Vue router integration

### Svelte (.svelte)

- Svelte-specific syntax for reactivity and binding (e.g., `bind:value`, `bind:group`)
- Uses Svelte's `{#each}` and `{#if}` blocks for lists and conditionals
- Standard HTML attributes and events

### Astro (.astro)

- Astro-specific snippets for UI components
- Standard HTML5 markup with support for Astro templating (e.g., `{items.map(...)}`)
- Ready for use in Astro component files

## Usage

1. Open a file with the appropriate language mode (HTML, JSX, TSX, Vue, Angular)
2. Type one of the snippet prefixes (e.g., `breadcrumbs`)
3. Press `Tab` to trigger the snippet
4. Use `Tab` to navigate through the placeholders

## Examples

### Breadcrumbs (HTML)

```html
<nav>
  <p>
    <a href="/">Home</a>
    <a href="/products">Products</a>
    <a href="/details">Product Details</a>
  </p>
</nav>
```

### Card (React)

```jsx
<article>
  <header>
    <h2>Card Title</h2>
  </header>
  <p>Card content goes here providing key information to the user.</p>
  <footer>
    <a href="#">Action Link</a>
  </footer>
</article>
```

### Navigation (Vue)

```html
<nav>
  <ul>
    <li><router-link to="/" exact>Home</router-link></li>
    <li><router-link to="/about">About</router-link></li>
    <li><router-link to="/products">Products</router-link></li>
    <li><router-link to="/contact">Contact</router-link></li>
  </ul>
</nav>
```

### Card (Svelte)

```svelte
<article>
  <header>
    <h2>Card Title</h2>
  </header>
  <p>Card content goes here providing key information to the user.</p>
  <footer>
    <a href="#">Action Link</a>
  </footer>
</article>
```

### Card (Astro)

```astro
<article>
  <header>
    <h2>Card Title</h2>
  </header>
  <p>Card content goes here providing key information to the user.</p>
  <footer>
    <a href="#">Action Link</a>
  </footer>
</article>
```

## Benefits of Semantic HTML

By focusing on semantics rather than styling, you gain:

- ♿ **Better accessibility** for screen readers and assistive technologies
- 🔍 **Improved SEO** with clearer document structure
- 📱 **Device independence** across browsers and platforms
- 🧠 **Easier maintainability** with code that describes its purpose
- 🚀 **Future-proofing** as the web evolves

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

[GitHub](https://github.com/letyassine/vsc-html-semantic-recipes)

## License

MIT
