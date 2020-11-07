<style>
  .header {
    display: flex;
    justify-content: space-evenly;
    border-bottom: 1px solid #eee;
    align-items: center;
  }

  .header p {
    line-height: 1;
  }
  .title {
    font-size: 1.2rem;
  }
  .price {
    font-size: 1rem;
    font-weight: 500;
  }

  .empty a {
    max-width: 70%;
    border: none;
    background-color: #222;
    color: white;
  }

  /* empty cart styles */
  .empty {
    margin: auto auto;
    text-align: center;
  }
  .empty h3 {
    font-size: 2rem;
  }
  .empty h3,
  .empty p {
    line-height: 1;
    margin: 0;
  }
  .empty p {
    margin-bottom: 2rem;
  }
  .empty a {
    width: 15rem;
    font-size: 1.1rem;
    text-decoration: none;
    padding: 0.4rem 5rem;
    white-space: nowrap;
  }

  .empty h3 {
    /* The font size should be big, but styles aren't being applied on prod / npm start */
    font-size: 4rem;
  }
</style>

<div class="header">
  <p class="title">YOUR CART</p>
  <p class="price">0 items - $0.00</p>
</div>

<div class="empty">
  <h3>Your Cart Is Empty</h3>
  <p>But wait.</p>
  <a href="/shop">Shop</a>
</div>
