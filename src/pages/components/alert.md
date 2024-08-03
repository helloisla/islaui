---
layout: ../../layouts/ComponentLayout.astro
title: 'Alert'
description: "Because nothing says important message like a good old alert box! Use these alerts to grab attention, deliver key information, and occasionally remind users that their devices have feelings too."
---

# Alert

<p class="mb-10">Because nothing says "important message" like a good old alert box! Use these alerts to grab attention, deliver key information, and occasionally remind users that their devices have feelings too.</p>

### Default alert

<p>Use the default alert for standard messages that need no frills. It's the plain bagel of alerts.</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-zinc-900" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><path d="M8 14s1.5 2 4 2 4-2 4-2"/><line x1="9" x2="9.01" y1="9" y2="9"/><line x1="15" x2="15.01" y1="9" y2="9"/></svg>
        <span class="sr-only">Default Alert</span>
        <div>
            <span>Nothing to see here, just default vibes.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-zinc-900" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><path d="M8 14s1.5 2 4 2 4-2 4-2"/><line x1="9" x2="9.01" y1="9" y2="9"/><line x1="15" x2="15.01" y1="9" y2="9"/></svg>
    <span class="sr-only">Default Alert</span>
    <div>
        <span>Nothing to see here, just default vibes.</span>
    </div>
</div>
```

### Outline alert

<p class="text-zinc-600">The outline alert is great for placeholder messages. Perfect for saying, “Details coming soon!”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-zinc-900 rounded-2xl border border-zinc-200" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="m12.5 17-.5-1-.5 1h1z"/><path d="M15 22a1 1 0 0 0 1-1v-1a2 2 0 0 0 1.56-3.25 8 8 0 1 0-11.12 0A2 2 0 0 0 8 20v1a1 1 0 0 0 1 1z"/><circle cx="15" cy="12" r="1"/><circle cx="9" cy="12" r="1"/></svg>
        <span class="sr-only">Outline Alert</span>
        <div>
            <span>Just the skeleton, no meat yet.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-zinc-900 rounded-2xl border border-zinc-200" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="m12.5 17-.5-1-.5 1h1z"/><path d="M15 22a1 1 0 0 0 1-1v-1a2 2 0 0 0 1.56-3.25 8 8 0 1 0-11.12 0A2 2 0 0 0 8 20v1a1 1 0 0 0 1 1z"/><circle cx="15" cy="12" r="1"/><circle cx="9" cy="12" r="1"/></svg>
    <span class="sr-only">Outline Alert</span>
    <div>
        <span>Just the skeleton, no meat yet.</span>
    </div>
</div>
```

### Ghost alert

<p class="text-zinc-600">Ghost alerts are perfect for subtle notifications. Use it when you want your message to haunt users gently.</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-zinc-900 rounded-2xl" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="M9 10h.01"/><path d="M15 10h.01"/><path d="M12 2a8 8 0 0 0-8 8v12l3-3 2.5 2.5L12 19l2.5 2.5L17 19l3 3V10a8 8 0 0 0-8-8z"/></svg>
        <span class="sr-only">Ghost Alert</span>
        <div>
            <span>Boo! Just kidding, it’s an alert.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-zinc-900 rounded-2xl" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="M9 10h.01"/><path d="M15 10h.01"/><path d="M12 2a8 8 0 0 0-8 8v12l3-3 2.5 2.5L12 19l2.5 2.5L17 19l3 3V10a8 8 0 0 0-8-8z"/></svg>
    <span class="sr-only">Ghost Alert</span>
    <div>
        <span>Boo! Just kidding, it’s an alert.</span>
    </div>
</div>
```

### Info alert

<p class="text-zinc-600">Info alerts are for delivering helpful information. Think of it as your app’s way of saying, “Fun fact!”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-cyan-950 rounded-2xl bg-cyan-300" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><line x1="12" x2="12" y1="8" y2="12"/><line x1="12" x2="12.01" y1="16" y2="16"/></svg>
        <span class="sr-only">Info Alert</span>
        <div>
            <span>Here’s a fun fact for you!</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-cyan-950 rounded-2xl bg-cyan-300" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><line x1="12" x2="12" y1="8" y2="12"/><line x1="12" x2="12.01" y1="16" y2="16"/></svg>
    <span class="sr-only">Info Alert</span>
    <div>
        <span>Here’s a fun fact for you!</span>
    </div>
</div>
```

### Success alert

<p class="text-zinc-600">Success alerts are for celebrating achievements. Ideal for letting users know they’ve hit the jackpot!</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-teal-600" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="M21.801 10A10 10 0 1 1 17 3.335"/><path d="m9 11 3 3L22 4"/></svg>
        <span class="sr-only">Success Alert</span>
        <div>
            <span>High five! You did it.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-teal-600" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><path d="M21.801 10A10 10 0 1 1 17 3.335"/><path d="m9 11 3 3L22 4"/></svg>
    <span class="sr-only">Success Alert</span>
    <div>
        <span>High five! You did it.</span>
    </div>
</div>
```

### Error alert

<p class="text-zinc-600">Error alerts are for when things go sideways. Use this to say, “Oops, something went wrong.”</p>

<div class="flex flex-wrap items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-rose-600" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><path d="m15 9-6 6"/><path d="m9 9 6 6"/></svg>
        <span class="sr-only">Error Alert</span>
        <div>
            <span>Oops! Something broke.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-white rounded-2xl bg-rose-600" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><path d="m15 9-6 6"/><path d="m9 9 6 6"/></svg>
    <span class="sr-only">Error Alert</span>
    <div>
        <span>Oops! Something broke.</span>
    </div>
</div>
```

### Warning alert

<p class="text-zinc-600">Warning alerts give users a heads-up. Perfect for saying, “Proceed with caution!”</p>

<div class="flex items-center justify-center gap-6 p-12 rounded-2xl border border-zinc-100">
    <div class="flex items-center gap-4 p-4 text-yellow-950 rounded-2xl bg-yellow-300" role="alert">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><line x1="12" x2="12" y1="8" y2="12"/><line x1="12" x2="12.01" y1="16" y2="16"/></svg>
        <span class="sr-only">Warning Alert</span>
        <div>
            <span>Heads up! Check twice.</span>
        </div>
    </div>
</div>

```html
<div class="flex items-center gap-4 p-4 text-yellow-950 rounded-2xl bg-yellow-300" role="alert">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shrink-0"><circle cx="12" cy="12" r="10"/><line x1="12" x2="12" y1="8" y2="12"/><line x1="12" x2="12.01" y1="16" y2="16"/></svg>
    <span class="sr-only">Warning Alert</span>
    <div>
        <span>Heads up! Check twice.</span>
    </div>
</div>
```