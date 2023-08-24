---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Lancet"
  text: "A powerful util function library of Go"
  tagline: Simple, powerful, and efficient.
  actions:
    - theme: brand
      text: Get Started
      link: /en/guide/getting_started
    - theme: alt
      text: View on GitHub
      link: https://github.com/duke-git/lancet
    # - theme: alt
    #   text: API Examples
    #   link: /api-examples
  image:
    src: /lancet_logo.png
    alt: lancet

features:
  - title: Powerful
    icon: 💪
    details: support 600+ go util functions. eg. string, slice, datetime, net, crypto, concurrency...
  - title: Modular by design
    icon: 🏗
    details: Each module is designed as a package with no coupling between modules.
  - title: Pure
    icon: 💅
    details: Only depends on two kinds of libraries, go standard library and golang.org/x.
  - title: Simple
    icon: 👏
    details: Well structure, test for every exported function.
---