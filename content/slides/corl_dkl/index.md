---
title: Scalable Deep Kernel Gaussian Process for Vehicle Dynamics in Autonomous Racing​
summary: An introduction to Deep Kernel Learning in Gaussian Process model for learning vehicle dynamics of a full-size racecar.
authors: [Jingyun Ning and Madhur Behl]
tags: []
categories: []
date: "2023-11-05"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: league
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

## Scalable Deep Kernel Gaussian Process for Vehicle Dynamics in Autonomous Racing

[Paper](https://openreview.net/pdf?id=zUiH8UUYDo) | [Conference](https://www.corl2023.org/)

---

### Vehicle Dynamics Modeling Is Challenging​

- Building dynamic vehicle models capable of modeling non-linear behaviors
- Obtaining physics-based model coefficients is often time and cost prohibitive.​
    - Learning drivetrain dynamics requires dyno testing
    - Understanding tire dynamics involves experimenting with specialized tire rigs.​
[Slide image](slides1.png)
---

### Approximate Dynamics Using Simpler Model

[single-track models](table.png)
- Approximate the observed dynamics with a simpler model (single-track model)
- Build a GP model to capture the residuals between the simpler model output and observations.
{{% fragment %}} Extended Kinematic Model **$+$** GP {{% /fragment %}}
{{% fragment %}} **$\approx$** {{% /fragment %}}
{{% fragment %}} Corrected Model {{% /fragment %}}
{{% fragment %}} **$\tilde$** {{% /fragment %}}
{{% fragment %}} **Observed Dynamics** {{% /fragment %}}
[Slide image](slides2.png)
---

## Code Highlighting

Inline code: `variable`

Code block:
```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

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
