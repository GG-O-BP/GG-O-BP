<h1 align="center">
  ✨ hiya!! i'm GG-O-BP! ✨
</h1>

<p align="center">
  <a href="https://github.com/GG-O-BP?tab=repositories">
    <img src="https://img.shields.io/badge/🌸_have_a_look_at_my_repos!-FF69B4?style=for-the-badge" />
  </a>
</p>

### 🎀 about me!!

hello hello!! i'm ever so pleased you've popped by my profile! 💕

i'm a developer and i absolutely *love* making things with **Gleam** and **Mendix**!! my proper job is building Mendix widgets using Gleam — isn't that just brilliant?! i also really like **Rust** and **Tauri** and honestly loads of other things too!! i can write code in more than **20 programming languages** which is quite a lot actually!! like JavaScript, TypeScript, C++ and ever so many more! 🌟

the developer i look up to the most is **Hoshino Lina** — she's absolutely wonderful and dead inspiring!! 💖

---

### 🌷 my pride and joy — glendix!!

my biggest achievement is [**glendix**](https://github.com/GG-O-BP/glendix) and i'm ever so proud of it!! 🎉

it's a **Gleam library** that talks to **React 19** and **Mendix Pluggable Widgets** — you can write proper Mendix widgets using *only* Gleam, no JSX needed at all!! how lovely is that!!

here's just a tiny peek at what it does:

- 🔮 **40 React Hooks** — useState, useEffect, and loads more!
- 🎨 **154+ event handlers** — that's absolutely masses!
- 🏷️ **108+ HTML attributes** and **85+ HTML tags**
- 🖌️ **58 SVG elements** and **97+ SVG attributes**
- 📦 **npm bindings** — use other people's React components with no fuss!
- 🧩 **.mpk widget support** — pop them in and they just work!
- 🛍️ **Marketplace downloader** — search and grab widgets from the terminal!

want to give it a go?? just run this and you're off!! 🚀

```bash
npx create-mendix-widget-gleam widget-name
```

it scaffolds a whole Mendix Pluggable Widget project written in Gleam — everything's set up and ready to go, no faffing about!! 🎁

```gleam
import mendraw/mendix.{type JsProps}
import redraw.{type Element}
import redraw/dom/attribute
import redraw/dom/html

// look how short and sweet it is!!
pub fn widget(props: JsProps) -> Element {
  let name = mendix.get_string_prop(props, "sampleText")
  html.div([attribute.class("my-widget")], [
    html.text("Hello " <> name),
  ])
}
```

---

### 🍓 things i love working with!!

<p align="center">
  <img src="https://img.shields.io/badge/Gleam-FFAFF3?style=for-the-badge&logo=gleam&logoColor=white" />
  <img src="https://img.shields.io/badge/Mendix-0595DB?style=for-the-badge&logo=mendix&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
</p>

<p align="center"><i>...and 20+ more!! i really do like learning new ones! 🌈</i></p>

---

### 🌻 my github stats!!

<p align="center">
  <img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=GG-O-BP&theme=rose_pine" />
  <img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=GG-O-BP&theme=rose_pine" />
</p>

---

<p align="center">
  <i>thanks ever so much for visiting!! have a lovely day!! 🌸💕✨</i>
</p>
