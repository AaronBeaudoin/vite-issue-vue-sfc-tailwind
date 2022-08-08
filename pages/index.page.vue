<template>
  <div style="padding: 20px;">
    <a style="display: block; text-decoration: underline;" href="/default-sfc">&gt; SSR — Vue SFC</a>
    <a style="display: block; text-decoration: underline;" href="/default-vanilla">&gt; SSR — Vue Render Function</a>
    <a style="display: block; text-decoration: underline; color: red;" href="/client-sfc">&gt; CSR — Vue SFC*</a>
    <a style="display: block; text-decoration: underline;" href="/client-vanilla">&gt; CSR — Vue Render Function</a>
    <hr style="margin: 20px 0;">
    <p style="color: red;">*Doesn't generate new CSS when classes are updated.</p>
    <p style="color: gray;">Also, note: HMR doesn't work for CSR pages due to a separate pending issue <a style="text-decoration: underline;" href="https://github.com/vitejs/vite/issues/9341">#9341</a>. Also, remember, Tailwind is caching each CSS class you generate, so try a different one for each page to reproduce the issue.</p>
  </div>
</template>
