---
layout: default
---

<div class="w-screen h-screen flex flex-col justify-center items-center text-slate-700 dark:text-slate-400 bg-white dark:bg-slate-900">
  <img class="w-48 mb-4 rounded-full" src="{{ '/assets/avatar.jpg' | prepend: site.baseurl }}">
  <h1 class="mb-6 font-sans text-2xl text-slate-900 hover:text-slate-600 dark:text-slate-200 dark:hover:text-slate-100">
    <a href="mailto:{{ site.email }}">{{ site.title }}</a>
  </h1>
  <p class="px-8 py-2 border-y-2 dark:border-gray-700 font-serif text-medium">{{ site.description }}</p>
</div>
