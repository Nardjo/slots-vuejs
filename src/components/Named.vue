<template>
  <div class="card">
    <slot name="title"></slot>
    <div class="card-body">
      <slot name="content"></slot>
    </div>
  </div>
</template>

<script></script>

<style>
.card {
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 16px;
  margin: 16px;
}
.card-header {
  font-weight: bold;
}
.card-body {
  padding-top: 8px;
}
</style>
