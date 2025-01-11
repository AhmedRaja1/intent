# 🚦 Lit Labs: Announcing @lit-labs/signals Package

Our newest package, **@lit-labs/signals**, is now available! 🎉  
Check out the announcement and start building today.

---

## 💻 **Get Started with Lit**  
Install Lit with:

```bash
npm i lit

✨ Simple: Skip the Boilerplate
Built on top of Web Components standards, Lit adds the essentials to make you happy and productive:

Reactivity
Declarative Templates
Thoughtful Features to Reduce Boilerplate
Every Lit feature is carefully designed with web platform evolution in mind.

⚡ Fast: Tiny Footprint, Instant Updates
With a minified and compressed size of around 5 KB, Lit keeps your bundle small and loading times short.
Rendering is blazing fast — it updates only the dynamic parts of your UI without rebuilding a virtual tree or diffing it with the DOM.

🌐 Web Components: Interoperable & Future-Ready
Lit components are native web components, making them:

Interoperable across frameworks
Shareable in any project
Maintainable for the future
Web components work anywhere HTML is used — whether it's a CMS, static site builder, or a JavaScript framework.

🚀 Example: Build a Simple Lit Component
Here’s a quick example of a Lit component using JavaScript/TypeScript:

javascript
Copy code
import {html, css, LitElement} from 'lit';
import {customElement, property} from 'lit/decorators.js';

@customElement('simple-greeting')
export class SimpleGreeting extends LitElement {
  static styles = css`p { color: blue }`;

  @property()
  name = 'Somebody';

  render() {
    return html`<p>Hello, ${this.name}!</p>`;
  }
}
Use it like this in your HTML:

html
Copy code
<simple-greeting name="World"></simple-greeting>
👉 Edit this example in the Lit Playground

🛠️ Lit Features at a Glance
✅ Custom Elements
Lit components are standard custom elements, meaning the browser treats them just like built-in elements.
Use them in:

Hand-written HTML
Framework code
CMS output
JavaScript
🎨 Scoped Styles
Lit uses Shadow DOM to scope your component’s styles.

Keeps selectors simple
Prevents style conflicts
Ensures styles are isolated
🔄 Reactive Properties
Declare reactive properties to model your component’s API and internal state.
Lit components efficiently re-render whenever a reactive property or corresponding HTML attribute changes.

📝 Declarative Templates
Lit templates use tagged template literals for a simple, expressive, and fast templating system:

HTML markup with inline JavaScript expressions
No custom syntax
No compilation required
🏗️ Build Anything with Lit
📦 Shareable Components
Need interactive content that drops into any site, built on any stack?
Lit components are natively supported by browsers, making them perfect for building shareable components.

🎨 Design Systems
Use Lit to create design systems that work across multiple frameworks in your organization.
Build one set of components that works for every team.

🌐 Sites and Apps
Lit can be used to progressively enhance a static site or to build entire apps.
With Web Components, Lit minimizes lock-in and promotes maintainability — update or migrate one component at a time without disrupting development.

🌟 Who’s Building with Lit?
Many forward-thinking organizations and projects use Lit to build scalable, maintainable components:

Design Systems	Frontend UI	Other Projects
Spectrum Web Components	Carbon Web Components	PWA Starter
Auro Design System	Lion Web Components	One Platform Components
Momentum UI	Pharos Design System	UI5 Web Components
Hilla Framework	Clarity Core	Wired Elements
📚 Explore Lit
Get hands-on with Lit through various learning resources:

Tutorials – Try live tutorials, no installation needed
Playground – Tinker with interactive examples
Documentation – Dive deep into Lit’s extensive docs
Get Started – See all the ways to begin building with Lit
🌐 Join the Lit Community
Connect with Lit and the Web Components community:

Lit Discord
Twitter
GitHub
Stack Overflow
All community participation is subject to Lit’s Code of Conduct — be excellent to each other!
