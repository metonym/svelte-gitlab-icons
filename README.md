# svelte-gitlab-icons

[![NPM][npm]][npm-url]

> [GitLab SVG icons](lib-url) as Svelte components.

<!-- REPO_URL -->

<!-- Try it in the [Svelte REPL](). -->

---

<!-- TOC -->

## Installation

**Yarn**

```bash
yarn add -D svelte-gitlab-icons
```

**NPM**

```bash
npm i -D svelte-gitlab-icons
```

## Usage

### Basic

```svelte
<script>
  import { Api, Fire, MergeRequestOpen } from "svelte-gitlab-icons";
</script>

<Api />
<Fire />
<MergeRequestOpen />
```

Refer to [ICON_INDEX.md](ICON_INDEX.md) for a list of supported icons.

### Direct import

Use the direct import for faster compiling during development.

**Note:** even if using base imports, unused imports are still tree shakeable by application bundlers like Rollup or webpack.

```html
<script>
  import Api from "svelte-gitlab-icons/lib/Api.svelte";
</script>
```

## Rendering icons using `svelte:component`

```svelte
<script>
  import * as icons from "svelte-gitlab-icons";
</script>

{#each Object.entries(icons) as [icon, component]}
  <div>
    <svelte:component this={component} />
    {icon}
  </div>
{/each}
```

## TypeScript

Svelte version 3.31 or greater is required to use this library with TypeScript.

## [Changelog](CHANGELOG.md)

## License

[MIT](LICENSE)

[npm]: https://img.shields.io/npm/v/svelte-gitlab-icons.svg?color=%237d4cdb&style=for-the-badge
[npm-url]: https://npmjs.com/package/svelte-gitlab-icons
