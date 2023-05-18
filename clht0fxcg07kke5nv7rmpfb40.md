---
title: "the new next is here"
datePublished: Fri Oct 28 2022 13:03:28 GMT+0000 (Coordinated Universal Time)
cuid: clht0fxcg07kke5nv7rmpfb40
slug: the-new-next-is-here

---

**Hello there!**

Hope everyone is doing fantastic! _Duh! Why are you even so enthusiastic about anything_, I hear you say. Well, I am excited because one of web's most beloved frameworks, [Next.js](https://nextjs.org) just got its new version - `13.0.0`. Announced at the [Next.js conference](https://nextjs.org/conf), it lays the foundations to be dynamic without limits.

It has created a lot of noise in the developer community as the version comes packing with an alpha version of a faster bundler, called Turbopack, as well as a redesigned approach to server rendering, routing, layouts, and data fetching. 

Let's talk about the new [Turbopack bundler](https://vercel.com/blog/turbopack), written in Rust. It is positioned as a successor to [Webpack](https://webpack.js.org/). Offering improved speed and a better architecture, Turbopack is a build system for JavaScript and TypeScript that is designed for incremental builds. Turbopack is 700 times faster than Webpack when working with large applications, the parent company of Next, [Vercel](https://vercel.com/) said.

We also have an enhanced version of the framework's filesystem-based routing system. It sets out to make it easy to lay out complex interfaces and maintain state across navigations, all while avoiding expensive re-renders. So now we get to save 8 seconds of build time each time we hit save xD!

The gods on the side of Next listened to our prayers and have improved on the existing `Image` component, making it easier to display images with less layout shift and better optimisation of files. On a similar front, there's also a new font system that automatically optimises fonts and automatically uses the CSS size-adjust property.

All's sweet as honey as we go on about the new changes. Let's have a look at what's going to break when we finally run [that](https://nextjs.org/docs/upgrading) `npm i next@latest react@latest react-dom@latest eslint-config-next@latest` command - 

- The minimum Node.js version has been bumped from `12.22.0` to `14.0.0`, since 12.x has reached end-of-life.
- The minimum React version has been bumped from `17.0.2` to `18.2.0`.
- The swcMinify configuration property was changed from false to true.
- The next/image import was renamed to `next/legacy/image`. The `next/future/image` import was renamed to `next/image`.
- The next/link child can no longer be `<a>`.

Huff! That was a LOT of fanboying over a single update. See you later folks, happy deving!