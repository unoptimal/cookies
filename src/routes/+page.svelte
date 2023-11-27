<script>
  // Add any JavaScript logic here
</script>

<style>
  .container {
      text-align: center;
      padding: 20px;
  }

  .images {
      display: flex;
      justify-content: center;
      align-items: center;
  }

  .images img {
      max-height: 400px; /* Increased size */
      width: auto;
      margin: 10px;
  }

  .plus-sign {
      font-size: 2em; /* Adjust size as needed */
      margin: 0 15px; /* Spacing around the plus sign */
  }

  @media (max-width: 600px) { /* Adjust breakpoint as needed */
      .images {
          flex-direction: column;
      }

      .plus-sign {
          display: block;
          margin: 10px 0;
      }
  }

  .description {
      font-size: 1.2em;
      margin-top: 20px;
  }
</style>

<div class="container">
  <h1>Danish Cookie Sewing Kits</h1>
  <div class="images">
      <img src="/cookies.png" alt="Royal Dansk Cookies Tin">
      <span class="plus-sign">+</span>
      <img src="/sewing.png" alt="Sewing Supplies">
  </div>
  <div class="description">
      <p>An assortment of sewing materials inside the Royal Dansk Butter Cookies' tin.</p>
      <p>BUY NOW!!!!</p>
  </div>
</div>
