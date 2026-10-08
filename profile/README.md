# 👋 Welcome to EpikodeLabs

We build open-source tools for people who want reactive applications without turning every feature into a maze of subscriptions, reducers, and cleanup code.

Our work brings fine-grained state and event-driven flows together in one practical model for modern JavaScript and TypeScript.

---

## 🌊 Streamix

![⚡ Fast](https://img.shields.io/badge/⚡%20Fast-transparent?style=flat&color=64748b)
![🧩 Composable](https://img.shields.io/badge/🧩%20Composable-transparent?style=flat&color=64748b)
![🪶 Lightweight](https://img.shields.io/badge/🪶%20Lightweight-transparent?style=flat&color=64748b)
![🔒 Fully Typed](https://img.shields.io/badge/🔒%20Fully%20Typed-transparent?style=flat&color=64748b)
![🔄 Sync%20%26%20Async](https://img.shields.io/badge/🔄%20Sync%20%26%20Async-transparent?style=flat&color=64748b)

Streamix is a lightweight, framework-agnostic reactive toolkit built around atoms, flows, scopes, and async iterators.

Use it for local state, derived values, asynchronous work, streams, and UI updates—without having to switch between unrelated state and async abstractions.

**Streamix v3 is live.** It brings a refined reactive core, pull-based operator pipelines, and a simpler way to model stateful and asynchronous application logic.

### What it helps with

- **State and async work in one model** — model values, requests, events, and streams with the same set of primitives.
- **Composable pipelines** — use familiar operators such as `debounce`, `switchMap`, `retry`, and `scan`.
- **Clear lifecycles** — scopes give related state and subscriptions an explicit owner and a reliable cleanup boundary.
- **Modern TypeScript ergonomics** — typed APIs designed to work naturally with `async` / `await` and `for await...of`.

```bash
npm install @epikodelabs/streamix
```

- **Documentation:** [epikodelabs.github.io/streamix](https://epikodelabs.github.io/streamix)
- **Repository:** [github.com/epikodelabs/streamix](https://github.com/epikodelabs/streamix)
- **Discussions:** [github.com/epikodelabs/streamix/discussions](https://github.com/epikodelabs/streamix/discussions)

---

## 🏗️ Actionstack

![📦 Feature Modules](https://img.shields.io/badge/📦%20Feature%20Modules-transparent?style=flat&labelColor=transparent&color=64748b)
![⚡ Reactive Stores](https://img.shields.io/badge/⚡%20Reactive%20Stores-transparent?style=flat&labelColor=transparent&color=64748b)
![🧷 Typed Actions](https://img.shields.io/badge/🧷%20Typed%20Actions-transparent?style=flat&labelColor=transparent&color=64748b)
![🎯 Selectors](https://img.shields.io/badge/🎯%20Selectors-transparent?style=flat&labelColor=transparent&color=64748b)
![💉 Dependency Injection](https://img.shields.io/badge/💉%20Dependency%20Injection-transparent?style=flat&labelColor=transparent&color=64748b)
![🏗️ Clean Composition](https://img.shields.io/badge/🏗️%20Clean%20Composition-transparent?style=flat&labelColor=transparent&color=64748b)

Actionstack is a modular state-management framework built on Streamix.

It is for applications that need more structure around state: feature modules, typed actions, selectors, dependencies, and asynchronous workflows that remain easy to follow as the codebase grows.

### What it helps with

- **Feature modules** — keep state, actions, selectors, and related logic together.
- **Typed actions and selectors** — make application changes explicit and keep derived state easy to reuse.
- **Dependency injection** — keep services replaceable and tests focused.
- **Composable architecture** — add, organize, and evolve application features without a monolithic store.

```bash
npm install @epikodelabs/actionstack
```

- **Repository:** [github.com/epikodelabs/actionstack](https://github.com/epikodelabs/actionstack)
- **Discussions:** [github.com/epikodelabs/actionstack/discussions](https://github.com/epikodelabs/actionstack/discussions)

---

## 💬 Community

Whether you are experimenting with reactive patterns, building a side project, or working on a large application, we would love to hear what you are making.

Questions, feedback, ideas, and contributions are welcome in GitHub Discussions. And if a project helps you, a star makes a real difference.
