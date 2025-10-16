<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
   <div class="rooms-container">
    <!-- Kitchen -->
    <div class="room" id="kitchen">
      <h2>Kitchen</h2>
      <button class="on" onclick="turnOn('kitchen')">Turn ON</button>
      <button class="off" onclick="turnOff('kitchen')">Turn OFF</button>
      <p class="status">Status: OFF</p>
    </div>

    <!-- Sitting Room -->
    <div class="room" id="sitting-room">
      <h2>Sitting Room</h2>
      <button class="on" onclick="turnOn('sitting-room')">Turn ON</button>
      <button class="off" onclick="turnOff('sitting-room')">Turn OFF</button>
      <p class="status">Status: OFF</p>
    </div>

    <!-- Restroom -->
    <div class="room" id="restroom">
      <h2>Restroom</h2>
      <button class="on" onclick="turnOn('restroom')">Turn ON</button>
      <button class="off" onclick="turnOff('restroom')">Turn OFF</button>
      <p class="status">Status: OFF</p>
    </div>

    <!-- Bedroom -->
    <div class="room" id="bedroom">
      <h2>Bedroom</h2>
      <button class="on" onclick="turnOn('bedroom')">Turn ON</button>
      <button class="off" onclick="turnOff('bedroom')">Turn OFF</button>
      <p class="status">Status: OFF</p>
    </div>
  </div>
  </main>
</template>
