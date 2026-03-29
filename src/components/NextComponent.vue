<template>
  <button class="next-btn">
    <img src="@/assets/arrow.png" alt="next" />
  </button>
</template>

<style scoped>
.next-btn {
  width: 80px;
  height: 80px;
  background: none;
  border: none;
  padding: 0;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
}

.next-btn img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  transition: 0.3s;
}

/* hover эффект */
.next-btn:hover img {
  transform: scale(1.05);
}
</style>
