Boltr Toolkit : Introduction
=====================================
[![Version](https://img.shields.io/npm/v/boltrswap-toolkit)](https://www.npmjs.com/package/boltrswap-toolkit)

![BoltrToolkit](https://github.com/boltrswap/Boltr-Toolkit/blob/main/toolkitreadme.jpg) 

**Well created by Boltr Dev. (2021)**

### Boltr Mission

Our mission is to build the world best decentralize exchange with a high performance trading engine and safety which can be trusted and enjoyed by users. Additionally we want to move the cryptocurrency exchange technology forward by providing support and add new features in the decentralize ecosystem


Boltr Toolkit is a set of React components and hooks used to build pages on Pancake's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add boltrswap-toolkit`

## Setup

### Theme

Before using Boltr Toolkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'boltrswap-toolkit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'boltrswap-toolkit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
