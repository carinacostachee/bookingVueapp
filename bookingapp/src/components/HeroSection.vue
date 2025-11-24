<script setup>
import '@/assets/hero.css'
import tableRestImage from '@/components/icons/table.png'
</script>

<template>
  <div class="hero-section">
    <h1 class="titlepage">Current tables in the restaurant:</h1>
    <div class="tables">
      <div class="tableId">
        <img :src="tableRestImage" alt="Restaurant table" />
        <h2 class="tableName">Table</h2>
      </div>
      <div class="tableId">
        <img :src="tableRestImage" alt="Restaurant table" />
        <h2 class="tableName">Table</h2>
      </div>
      <div class="tableId">
        <img :src="tableRestImage" alt="Restaurant table" />
        <h2 class="tableName">Table</h2>
      </div>
      <div class="tableId">
        <img :src="tableRestImage" alt="Restaurant table" />
        <h2 class="tableName">Table</h2>
      </div>
    </div>
  </div>
</template>
