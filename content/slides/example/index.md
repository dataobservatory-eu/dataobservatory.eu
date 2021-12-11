---
title: Slides
summary: Data Curation With Reprex
authors: []
tags: []
categories: []
date: "2020-01-21T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap" rel="stylesheet">

# Data Curation With Reprex

[Reprex](https://wowchemy.com/) | [Data Curation](https://owchemy.com/docs/managing-content/#create-slides)

---

## Presentation Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---
## Novel Data Products

  <section>
  <table class="reveal" style='font-family:"Roboto Condensed"; font-size:60%'>
   <col width="240">
   <col width="480">
    <tr>
      <td><img data-src="/media/img/blogposts_2021/global_problem_1_climate_change_5_plots.png" width="240" height="160" /></br></br> See our <a href="https://greendeal.dataobservatory.eu/post/2021-11-19_global_problem/" target = "_blank">100,000 Opinions on the Most Pressing Global Problem</a> blogpost.</td>
      <td valign='top'>Official statistics at the national and European levels follow legal regulations, and in the EU, compromises between member states. New policy indicators often appear 5-10 years after demand appears. We employ the same methodology, software, and often even the same data that Eurostat might use to develop policy indicators, but we do not have to wait for a political and legal consensus to create new datasets. </td>
    </tr>
  </table>
  </section>

---

## Data Curation

If you do not find the data for your research, reporting or evaluation project, it does not mean that the data does not exist. It does not mean that the data is not available for *free*.

---

## Fragments

Make content appear incrementally



{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

<Press `Space` to play!>

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://github.com/wowchemy/wowchemy-hugo-modules/discussions)

[Documentation](https://wowchemy.com/docs/managing-content/#create-slides)
