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