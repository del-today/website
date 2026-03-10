---
layout: changelog
permalink: /changelog/
title: changelog
---

## February 2026

Hello, Dilli!

## March 2026
- `Fixed` [Urbanaut](/cal/urbanaut)

<script>
	document.querySelectorAll('article code').forEach(el => {
		const content = el.textContent.toLowerCase().replace(/\s+/g, '-');
		el.className += ' badge-' + content;
	});

</script>