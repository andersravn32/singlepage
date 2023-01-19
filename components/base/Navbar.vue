<template>
  <nav class="navbar">
    <BaseLogo />
    <ul>
      <li>
        <NuxtLink to="/about">Om os</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/services">Tidligere cases</NuxtLink>
      </li>
      <li>
        <BaseButton>Kontakt os</BaseButton>
      </li>
    </ul>
  </nav>
</template>

<style>
.navbar {
  @apply fixed z-10 top-0 left-0 right-0 container mx-auto flex items-center justify-between p-4;
}

.navbar ul {
  @apply flex items-center space-x-12 text-slate-900 text-sm;
}
</style>
