# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`?

Describe what makes a unit responsive and why that matters when building a website.

Static units like px are fixed values that don't change regardless of screen size or parent container size. Responsive units like % and vh and vw scale based on the screen or container dimensions. Responsive units matter because they allow websites to adapt and look good on different screen sizes, from phones to desktop. When you use static pixels, elements can become too large on mobile or too small on large screens, making the site harder to use. Responsive units makes sure content automatically adjusts to fit the space, which is important for creating websites that work well across all devices.






---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?

With width: 400px;, the image will always be exactly 400 pixels wide, which is larger than most phone screens. On a small screen, the image will overflow its container, breaking the layout. With width: 50%;, the image scales to 50% of its parent container's width. On a small mobile screen, it will be proportionally smaller and fit nicely; on a large desktop screen, it will be larger. The percentage rule behaves better because it adapts to any screen size, keeping the image responsive and preventing layout overflow.



