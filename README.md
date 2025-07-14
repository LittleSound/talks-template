# Talks Template like [antfu/talks](https://github.com/antfu/talks)

Start writing Slides with markdown soon, using [Slidev](https://github.com/slidevjs/slidev)!

## Features

- ⚡️ [Slidev](https://github.com/slidevjs/slidev) - write slides in markdown
- 🍱 Manage all your slides in a repo
- 🎯 [picker](https://github.com/littlesound/picker) - Choose a repository in the terminal to execute the script
- 📱 Write interactive slides with [Vue](https://vuejs.org/)
- 📦 [pnpm](https://pnpm.io/) - package manager
- 😃 [Use icons from any icon sets with classes](https://github.com/antfu/iconify-json)

## Try it now!

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/LittleSound/talks-template/generate).

### Clone to local

If you prefer to do it manually with the cleaner git history

```bash
npx degit LittleSound/talks-template my-talks
cd my-talks
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```

## Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Change the author name in `LICENSE`
- [ ] Remove the `.github` folder which contains the funding info
- [ ] Use `README-template.md` to replace `README.md`
- [ ] Copy the `0000-00-00` folder and start creating your actual talk
- [ ] Find the TODO tags in the file to learn more

And, enjoy :)

## Usage:

### Development

```bash
pnpm dev
```

visit <http://localhost:3030>

Edit the `<your talk folder>/src/slides.md` to see the changes.

Learn more about Slidev at the [documentation](https://sli.dev/).

### Build

To build the Slides Website, run

```bash
pnpm build
```

### Export to PDF

To export the Slides to PDF, run

```bash
pnpm export
```

the PDF will be generated in the `<your talk folder>/slides.pdf` folder.

## Sponsors

<p align="center">
  <a href="https://github.com/sponsors/LittleSound">
    <img src="https://cdn.jsdelivr.net/gh/littlesound/sponsors/sponsors.svg"/>
  </a>
</p>

<p align="center">
  This project is made possible by all the sponsors supporting my work <br>
  You can join them at my sponsors profile:
</p>
<p align="center"><a href="https://github.com/sponsors/LittleSound"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86&style=for-the-badge" /></a></p>
