# BestBooks

> **আপনার নিজের পাঠের তাক।**

BestBooks হলো বাংলা ও English গল্প, উপন্যাস, কবিতা, জীবনী ও জ্ঞানভিত্তিক বইয়ের একটি curated digital shelf। প্রকল্পটির লক্ষ্য হলো পাঠকদের জন্য একটি শান্ত, দ্রুত এবং সহজে অনুসন্ধানযোগ্য বই-আবিষ্কারের জায়গা তৈরি করা। বিদ্যমান catalog-এর কোনো গল্প বা বইয়ের নাম বাদ দেওয়া হয়নি।

## Features

সাইটে আছে instant search, বাংলা/English filter, author-based sorting, মূল তালিকা থেকে A–Z/Z–A সাজানো, localStorage-ভিত্তিক “আমার পছন্দ” তালিকা, dark/light theme, “আজকের পছন্দ” random picker, বইয়ের তথ্য copy action এবং Google/PDF quick search। Responsive layout, keyboard shortcut (`/` search, `Esc` clear), semantic HTML, accessible labels এবং reduced-motion support-ও যুক্ত আছে।

## Live site

[humayunshariarhimu.github.io/BestBooks](https://humayunshariarhimu.github.io/BestBooks/)

## Local development

এটি dependency-free static site। সরাসরি `index.html` খুলতে পারেন, অথবা স্থানীয় server চালাতে পারেন:

```bash
python3 -m http.server 8000
```

তারপর `http://localhost:8000` খুলুন।

## Publishing

GitHub Pages `main` branch-এর root folder থেকে deploy করা হয়। `index.html` এবং `public/manus-routes.json`-ই প্রয়োজনীয় runtime files; কোনো build step বা framework নেই।

## Credits & license

Curated by **Humayun Shariar Himu**। Repository is distributed under the [Apache License 2.0](LICENSE).
