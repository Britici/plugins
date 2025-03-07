# emotion

The official plugin for emotion css-in-js library.

## Configuration

The plugin uses the same config as described in [Next emotion documentation](https://nextjs.org/docs/advanced-features/compiler#emotion).

```js
{
  jsc: {
    ...
   experimental: {
     plugins: [ ['@swc/plugin-emotion', {
      // default is true. It will be disabled when build type is production.
      sourceMap?: boolean,
      // default is 'dev-only'.
      autoLabel?: 'never' | 'dev-only' | 'always',
      // default is '[local]'.
      // Allowed values: `[local]` `[filename]` and `[dirname]`
      // This option only works when autoLabel is set to 'dev-only' or 'always'.
      // It allows you to define the format of the resulting label.
      // The format is defined via string where variable parts are enclosed in square brackets [].
      // For example labelFormat: "my-classname--[local]", where [local] will be replaced with the name of the variable the result is assigned to.
      labelFormat?: string,
    }] ]
   }
}
```

## Credit

Source code for plugin itself (not transforms) are copied from https://github.com/IvanRodriCalleja/emotion-swc-plugin

# @swc/plugin-emotion

## 3.0.7

### Patch Changes

- 41a8f56: Update swc_core to v0.95.x

## 3.0.6

### Patch Changes

- fc30490: Update swc_core to v0.93.0

## 3.0.5

### Patch Changes

- 016c13b: Fix transform not applying to css calls inside of functions

## 3.0.4

### Patch Changes

- 0f38844: Publish all chanages

## 3.0.3

### Patch Changes

- 1cc9eda: Update dependencies

## 3.0.2

### Patch Changes

- 247cca6: Update rustc to 'nightly-2024-04-16'

## 3.0.1

### Patch Changes

- 876bbce: Update swc_core to 0.92.x

## 3.0.0

### Major Changes

- 8e91d39: Update swc_core to 0.91.x

## 2.5.124

### Patch Changes

- f4df366: Update swc_core

## 2.5.123

### Patch Changes

- c88b22b: Align package metadata

## 2.5.122

### Patch Changes

- a3cc4fb: Organize pacakge metadata

## 2.5.121

### Patch Changes

- e9e78ef: Update swc crates

## 2.5.120

### Patch Changes

- 6096d6d: Fix plugin version schema issue

## 2.5.119

### Patch Changes

- 37d3aaf: Depend on the swc download counter package

## 2.5.118

### Patch Changes

- 096d823: Strip line comments correctly

## 2.5.117

### Patch Changes

- 8bd92c7: swc_core 0.90.x

## 2.5.116

### Patch Changes

- 47db290: Fix string escaping issue

## 2.5.115

### Patch Changes

- 906b5dd: Fix panic when trying to unwrap None on setting the context for a function name

## 2.5.114

### Patch Changes

- 4ef0b7f: Add changelog to the readme

## 2.5.113

### Patch Changes

- 4e72680: swc_core@0.88.0

## 2.5.112

### Patch Changes

- 16bb4d8: swc_core@0.82.x
