<template>
<div>
    <nav class="flex justify-center mt-5">
        <NuxtLink class="px-4 py-2 border" to="/">Home</NuxtLink>
        <!-- <NuxtLink to="/welcome">Welcome</NuxtLink> -->
    </nav>
    <main>
          <slot />
    </main>
</div>
</template>