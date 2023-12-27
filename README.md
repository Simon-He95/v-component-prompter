<p align="center">
<img height="200" src="./assets/kv.png" alt="v component prompter">
</p>
<p align="center"> English | <a href="./README_zh.md">简体中文</a></p>

Bring `props`, `emitEvents` and `expose methods` tips to some imported custom components in Vue development.

## Example
- I want to know which `props` or `event` types of components I imported can pass and correspond to them.
![demo](/assets/1.jpg)

- Maybe the attributes in this defineProps are exported from other `ts` files.
![demo](/assets/2.jpg)
![demo](/assets/3.jpg)

- When you hover to the `tagName` of this component, there will be a table listing specific passable parameter information.
![demo](/assets/4.jpg)

- When you hover to a specific attribute on the component attribute, the type of this attribute will be prompted. If there is a comment in the component, it will also be prompted when hover.
![demo](/assets/5.jpg)

![demo](/assets/demo.gif)

## Auto Import

In the latest version, we can detect `"auto-imports.d.ts"` and provide smart tips for `"props"`, `"events"` and `"methods"`


## :coffee:

[buy me a cup of coffee](https://github.com/Simon-He95/sponsor)


## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/Simon-He95/sponsor/sponsors.svg">
    <img src="https://cdn.jsdelivr.net/gh/Simon-He95/sponsor/sponsors.png"/>
  </a>
</p>
