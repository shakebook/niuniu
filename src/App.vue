<script setup lang="ts"></script>

<template>
  <div class="chat-notification">
    <div class="chat-notification-logo-wrapper">
      <img class="chat-notification-logo" src="/vite.svg" alt="ChitChat Logo" />
    </div>
    <div class="chat-notification-content">
      <h4 class="chat-notification-title text-rose-800">ChitChat</h4>
      <p class="chat-notification-message">You have a new message!</p>
      <p class="text-rose-800 hover:text-sky-400">You have a new message!</p>
      <p class="text-sky-400/100">The quick brown fox...</p>
      <p class="text-sky-400/75">The quick brown fox...</p>
      <p class="text-sky-400/50">The quick brown fox...</p>
      <p class="text-sky-400/25">The quick brown fox...</p>
      <p class="text-sky-400/0">The quick brown fox...</p>
      <p class="text-blue-600/50 bg-green-500">Thkkjkjkjkjk..</p>
    </div>
  </div>
</template>

<style scoped>
.chat-notification {
  display: flex;
  max-width: 24rem;
  margin: 0 auto;
  padding: 1.5rem;
  border-radius: 0.5rem;
  background-color: #fff;
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1),
    0 10px 10px -5px rgba(0, 0, 0, 0.04);
}
.chat-notification-logo-wrapper {
  flex-shrink: 0;
}
.chat-notification-logo {
  height: 3rem;
  width: 3rem;
}
.chat-notification-content {
  margin-left: 1.5rem;
  padding-top: 0.25rem;
}
.chat-notification-title {
  color: #1a202c;
  font-size: 1.25rem;
  line-height: 1.25;
}
.chat-notification-message {
  color: #718096;
  font-size: 1rem;
  line-height: 1.5;
}
</style>
