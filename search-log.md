
# 調査ログ

## 2024/05/25

### Next.js + React + react-cytoscape でネットワーク図作成

- 起動時以下のエラーに遭遇
  - Microbundle Compile Error Next.js · Issue #117 · plotly/react-cytoscapejs
    - <https://github.com/plotly/react-cytoscapejs/issues/117>
    - →react-cytoscapejsのpackage.jsonのexportsを変えてあげないと、
    - commonjsとesmoduleの解決ができなくってエラーになってたみたい
    - package.jsonにはConditional exportsという機能があるのね という話でした


