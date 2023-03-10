# You can use NakedJSX to make a nice website.

## Features

- Build HTML files using JSX templates
- Precompile JSX for use in client JavaScript code
- Client JavaScript compression
- Optional inlining of Client JavaScript within generated HTML
- Embed predefined values at build time
- Scoped CSS extraction from JSX css="..." attributes
- CSS nesting
- CSS deduplication and compression
- Configurable import path alias prefixes
- Raw file asset embedding (useful for inline SVG)
- Generate scaled image sourcesets (via @nakedjsx/plugin-asset-image)
- Conversion of source images to webp (via @nakedjsx/plugin-asset-image)
- Live-refresh development server
- Production build optimisation
- Asset import plugin system
- Fast build time

## Conservative dependency choices

| Node | |
| - | - |
| babel* | Compile JavaScript and JSX down to browser-friendly JavaScript, and host JSX CSS processing plugin. |
| chokidar | Watch the file system for changes. |
| csso | CSS compression. |
| postcss* | Compile modern nested CSS into flat CSS. |
| rollup* | Produce self-contained JavaScript bundles, idenify inter-file dependencies, and host custom asset import processes. |
| terser | JavaScript compression for production builds of client JavaScript code. |

\* Additional plugins @babel/plugin-transform-react-jsx and @babel/preset-env plugins.

† Plus postcss-nested plugin.

§ Plus @rollup/plugin-babel, @rollup/plugin-commonjs, @rollup/plugin-json, and @rollup/plugin-node-resolve plugins.

| OS | |
| - | - |
| GraphicsMagick | Image sourceset scaling and conversion (If using @nakedjsx/plugin-asset-image) |

Where practical, required functionality is implemented directly within NakedJSX.

## Getting started

Coming soon - an npx command to generate an example project.