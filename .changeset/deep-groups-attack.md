---
"@robot-inventor/tsconfig-base": minor
---

feat: explicitly disable `noUncheckedSideEffectImports` to accommodate the latest TypeScript changes

Previously, `noUncheckedSideEffectImports` was disabled by default in TypeScript, but it has recently been enabled by default. Since this option can break existing projects that use CSS Modules, this commit explicitly disables it to maintain the previous behavior.

Ref:

- https://github.com/microsoft/TypeScript/pull/62443
- https://github.com/microsoft/typescript-go/pull/2864
