This is the [Biome](https://biomejs.dev/) configuration used by [John
Karahalis](https://www.johnkarahalis.com) in his personal projects.

## Installation

Run `npm install --save-dev @openjck/biome-config`.

## Usage

1. If you haven't already, install Biome by running `npm install --save-dev
   @biomejs/biome`.
2. Run `npx biome init --jsonc`.
3. Edit _biome.jsonc_.
    1. Remove all lines except for the line defining the `$schema` property.
    2. Add the following line: `"extends": ["@openjck/biome-config"],`
