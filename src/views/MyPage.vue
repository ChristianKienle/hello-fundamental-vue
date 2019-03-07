<template>
  <FdSection title="My Page">
    <FdPanel>
      <p>I am a paragraph</p>
      <router-link :to="{ name:'about' }">Navigate to About</router-link>
    </FdPanel>
  </FdSection>
</template>
