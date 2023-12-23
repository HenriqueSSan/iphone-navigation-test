<script lang="ts">
</script>

<main>
  <div class="sticky-footer">
    <div class="sticky-footer__item">
      <img src="http://via.placeholder.com/50" alt="" />
      Item name
    </div>
    <div class="sticky-footer__item">
      <img src="http://via.placeholder.com/50" alt="" />
      Item name
    </div>
    <div class="sticky-footer__item">
      <img src="http://via.placeholder.com/50" alt="" />
      Item name
    </div>
    <div class="sticky-footer__item">
      <img src="http://via.placeholder.com/50" alt="" />
      Item name
    </div>
  </div>
</main>

<style lang="scss">
  .sticky-footer {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    position: fixed;
    bottom: 0;
    width: 100%;
    background: white;

    &__item {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 1rem 0;
      padding-bottom: calc(1rem + env(safe-area-inset-bottom));

      img {
        margin-bottom: 0.5rem;
        border-radius: 50%;
      }
    }
  }
</style>
