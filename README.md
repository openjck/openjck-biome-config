This is the [Biome](https://biomejs.dev/) configuration used by [John
Karahalis](https://www.johnkarahalis.com) in his personal projects.

## Usage

### Using this config as your only Biome config

1. Run `npm install --save-dev @biomejs/biome @openjck/biome-config`.
2. Run `npx biome init --jsonc`.
3. Edit _biome.jsonc_.
    1. Remove all properties and their values except for `$schema`.
    2. Add the following line: `"extends": ["@openjck/biome-config"],`

### Extending this config in your existing Biome config

1. Install this config by running `npm install --save-dev
   @openjck/biome-config`.
2. Add the following line to your Biome config: `"extends":
   ["@openjck/biome-config"],`
