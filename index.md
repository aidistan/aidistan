---
layout: default
---

<div class="w-screen h-screen flex flex-col justify-center items-center">
  <img class="w-48 mb-4 rounded-full" src="{{ '/assets/avatar.jpg' | prepend: site.baseurl }}">
  <h1 class="mb-6 font-sans text-2xl hover:text-slate-500">
    <a href="mailto:{{ site.email }}">{{ site.title }}</a>
  </h1>
  <p class="px-8 py-2 border-y-2 font-serif text-medium">{{ site.description }}</p>
</div>
