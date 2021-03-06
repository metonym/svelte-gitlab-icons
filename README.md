# svelte-gitlab-icons

[![NPM][npm]][npm-url]

> [GitLab SVG icons](https://gitlab.com/gitlab-org/gitlab-svgs) as Svelte components.

<!-- REPO_URL -->

Try it in the [Svelte REPL](https://svelte.dev/repl/43aa7623339d47d1b4403a1a35f60446).

---

<!-- TOC -->

## Installation

```bash
# Yarn
yarn add -D svelte-gitlab-icons

# npm
npm i -D svelte-gitlab-icons

# pnpm
pnpm i -D svelte-gitlab-icons
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

Directly import an icon for faster compiling during development.

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

## [Changelog](CHANGELOG.md)

## License

[MIT](LICENSE)

[npm]: https://img.shields.io/npm/v/svelte-gitlab-icons.svg?color=%23e2432a&style=for-the-badge
[npm-url]: https://npmjs.com/package/svelte-gitlab-icons
