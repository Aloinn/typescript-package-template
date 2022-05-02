---
title: TypesScript Package Template
created: '2021-10-18T15:47:53.586Z'
modified: '2021-10-18T15:57:53.365Z'
---

# TypesScript Package Template

Template contains setup for creating TypeScript npm packages.

## Setup and Usage

**Build**
```bash
npm prepare
```

**Test**
In package directory run the following:
```bash
cd ~/directory 
npm link
```

In other package directory 
```bash
cd ~/directory
npm link name_of_package
```

**Publish**
```bash
npm publish
```