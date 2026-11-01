<script setup>
</script>
<template>
  <div class = "app">
    <header class = "site-header">
      <div class = "logo">
      <svg class="logo-mark" viewBox="0 0 64 64" aria-hidden="true">
        <path d="M16 24h28v14a12 12 0 0 1-12 12h-4a12 12 0 0 1-12-12V24z"
              fill="none" stroke="currentColor" stroke-width="3" stroke-linejoin="round"/>
        <path d="M44 28h4a6 6 0 0 1 0 12h-4"
              fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
        <path d="M24 14c0 4-3 4-3 8M32 14c0 4-3 4-3 8M40 14c0 4-3 4-3 8"
              fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
      </svg>
      <div class = "logo-text">
        <h1>This<span class = "amp">&</span>That</h1>
        <p>Find your new favorite cafe!</p>
      </div>
      </div>
    </header>
    <main>
      <section class = "search-section">
        <input
          type = "text"
          placeholder = "Search for a beverage..."
          />
          <button>Search</button>
        </section>
        <section class = "filters">
          <button>Open Now</button>
          <button>Price</button>
          <button>Rating</button>
          <button>Distance</button>
        </section>
        <section class = "results">
          <h2>Cafe's near you...</h2>
            <div class = "cafe-card">
              <h3>Cafe Name</h3>
              <p>Rating: 4.5</p>
              <p>Price: $$</p>
              <p>Distance: 0.5 miles</p>
            </div>
        </section>      
      </main>    
  </div>
</template>
<style scoped>
</style>
