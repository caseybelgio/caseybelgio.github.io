---
layout: home
author_profile: true
---

Hi, I’m Casey 👋  
I’m a Product Manager focused on building user-centered fintech and SaaS products.
<section id="home">
  <h2>Welcome!</h2>
  <p>This is my PM portfolio site. Click the frog 🐸 for a surprise!</p>
  <img id="frog" src="assets/images/frog.svg" alt="frog" style="width:50px; cursor:pointer;" />
</section>
const frog = document.getElementById('frog');
frog.addEventListener('click', () => {
  alert('Ribbit! You found the frog Easter egg 🐸!');
});
