<script setup>
</script>
<template>
  <div class = "app">
    <header>
      <h1>This&That</h1>
      <p>Find your new favorite cafe!</p>
    </header>
    <main>
      <section class = "search-section">
        <input
          type = "text"
          placeholder = "Search for a bev"
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
          <h2>Cafe's near you</h2>
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
