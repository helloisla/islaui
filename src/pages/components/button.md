---
layout: ../../layouts/ComponentLayout.astro
title: 'Button'
description: "Buttons are your interactive magic keys, designed to make things happen with just a click. Use them to turn user intentions into actions, or just to feel like a tech wizard.

"
---

# Button

<p class="mb-10">Buttons are your interactive magic keys, designed to make things happen with just a click. Use them to turn user intentions into actions, or just to feel like a tech wizard.
</p>

### Default button

<p>The default button is your everyday, reliable option. It’s like the classic black dress—always appropriate and never out of style.
</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-white bg-zinc-900 hover:bg-zinc-800 focus:outline-none focus:ring-4 focus:ring-zinc-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-white bg-zinc-900 hover:bg-zinc-800 focus:outline-none focus:ring-4 focus:ring-zinc-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```

### Outline button

<p>The outline button brings a touch of minimalist elegance. It’s like the default button but with a stylish border that says, “I’m here, but I’m also cool.”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-zinc-900 border border-zinc-200 hover:bg-zinc-100 focus:outline-none focus:ring-4 focus:ring-zinc-100 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-zinc-900 border border-zinc-200 hover:bg-zinc-100 focus:outline-none focus:ring-4 focus:ring-zinc-100 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```

### Ghost button

<p>The ghost button is for when you want to keep things subtle. It’s a button that’s there but almost invisible—perfect for when you don’t want to make a fuss.
</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-zinc-900 hover:bg-zinc-100 focus:outline-none focus:ring-4 focus:ring-zinc-200 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-zinc-900 hover:bg-zinc-100 focus:outline-none focus:ring-4 focus:ring-zinc-200 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```

### Disabled button

<p>The disabled button is like a “Do Not Disturb” sign for your UI. It’s there, looking all button-like, but with a friendly message saying, “I’m taking a break—please try again later.”
</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-zinc-500 bg-zinc-100 focus:outline-none font-medium rounded-full text-sm/6 px-4 py-2 text-center cursor-not-allowed" disabled>Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-zinc-500 bg-zinc-100 focus:outline-none font-medium rounded-full text-sm/6 px-4 py-2 text-center cursor-not-allowed" disabled>Button</button>
```

### Info button

<p>The info button is your go-to for sharing helpful tidbits. It’s like a friendly nudge saying, “Hey, here’s some extra info!”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-cyan-950 bg-cyan-300 hover:bg-cyan-400 focus:outline-none focus:ring-4 focus:ring-cyan-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-cyan-950 bg-cyan-300 hover:bg-cyan-400 focus:outline-none focus:ring-4 focus:ring-cyan-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```

### Success button

<p>The success button is all about celebrating achievements. Use it to say, “You did it!” and give users a high-five in button form.</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-white bg-teal-600 hover:bg-teal-700 focus:outline-none focus:ring-4 focus:ring-teal-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-white bg-teal-600 hover:bg-teal-700 focus:outline-none focus:ring-4 focus:ring-teal-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```
### Error button

<p>The error button is for when something goes awry. It’s like the digital equivalent of a red flag—perfect for saying, “Oops, something went wrong.”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-white bg-rose-600 hover:bg-rose-700 focus:outline-none focus:ring-4 focus:ring-rose-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-white bg-rose-600 hover:bg-rose-700 focus:outline-none focus:ring-4 focus:ring-rose-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```

### Warning button

<p>The warning button is for giving a heads-up. It’s your alert in button form, gently saying, “Proceed with caution!”.</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <button type="button" class="inline-flex items-center text-yellow-950 bg-yellow-300 hover:bg-yellow-400 focus:outline-none focus:ring-4 focus:ring-yellow-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
</div>

```html
<button type="button" class="inline-flex items-center text-yellow-950 bg-yellow-300 hover:bg-yellow-400 focus:outline-none focus:ring-4 focus:ring-yellow-300 font-medium rounded-full text-sm/6 px-4 py-2 text-center">Button</button>
```