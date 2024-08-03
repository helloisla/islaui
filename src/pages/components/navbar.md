---
layout: ../../layouts/ComponentLayout.astro
title: 'Navbar'
description: "Navbar"
---

# Navbar

<p class="mb-10">Because nothing says "important message" like a good old alert box! Use these alerts to grab attention, deliver key information, and occasionally remind users that their devices have feelings too.</p>

### Default navbar

<p>Use the default alert for standard messages that need no frills. It's the plain bagel of alerts.</p>

<header class="w-full bg-primary">
  <div class="container mx-auto max-w-[1280px] flex items-center justify-between px-4 py-3">
    <a class="flex items-center" href="#" rel="ugc">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
        class="h-6 w-6 text-primary-foreground"
      >
        <path d="m8 3 4 8 5-5 5 15H2L8 3z"></path>
      </svg>
      <span class="ml-2 text-lg font-semibold text-primary-foreground">Acme Inc</span>
    </a>
    <nav class="hidden md:flex items-center space-x-6">
      <a class="text-primary-foreground hover:underline" href="#" rel="ugc">
        Home
      </a>
      <a class="text-primary-foreground hover:underline" href="#" rel="ugc">
        About
      </a>
      <a class="text-primary-foreground hover:underline" href="#" rel="ugc">
        Services
      </a>
      <a class="text-primary-foreground hover:underline" href="#" rel="ugc">
        Contact
      </a>
    </nav>
    <button class="items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 bg-primary text-primary-foreground hover:bg-primary/90 h-10 px-4 py-2 hidden md:inline-flex">
      Get Started
    </button>
    <button
      class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 border border-input bg-background hover:bg-accent hover:text-accent-foreground h-10 w-10 md:hidden"
      type="button"
      aria-haspopup="dialog"
      aria-expanded="false"
      aria-controls="radix-:r6:"
      data-state="closed"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
        class="h-6 w-6 text-primary-foreground"
      >
        <line x1="4" x2="20" y1="12" y2="12"></line>
        <line x1="4" x2="20" y1="6" y2="6"></line>
        <line x1="4" x2="20" y1="18" y2="18"></line>
      </svg>
      <span class="sr-only">Toggle navigation menu</span>
    </button>
  </div>
</header>

```html
<div></div>
```