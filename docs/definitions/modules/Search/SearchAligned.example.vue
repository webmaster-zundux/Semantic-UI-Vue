<template lang="html">
  <sui-search aligned="right" action="search category">
    <template v-slot:input="{ props, handlers }">
      <sui-input
        v-bind="props"
        v-on="handlers"
        icon="search"
        placeholder="Common animals..."
      />
    </template>
  </sui-search>
</template>
