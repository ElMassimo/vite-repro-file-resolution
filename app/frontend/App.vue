<template>
  <h1>Static File Serving</h1>

  <div style="padding-top:1em;">
    <p>Image inside the root:</p>
    <img src="@/entrypoints/inner_logo.png" alt="Vue logo">
  </div>

  <div style="padding-top:1em;">
    <p>Image outside the root, served with <pre style="display:inline">@fs</pre>:</p>
    <img src="@/outer_logo.png" alt="Vite Ruby logo">
  </div>
</template>
