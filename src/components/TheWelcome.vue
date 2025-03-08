<script setup>

import { Input } from '@/components/ui/input'
import { Label } from '@/components/ui/label'

</script>

<template>

<div class="grid grid-cols-3 grid-rows-2 gap-4">
    <div class="flex">
      <Label for="input1">Max width:</Label>
      <Input id="input1" type="text" />
    </div>
    <div class="flex">
      <Label for="input2">Gutter width:</Label>
      <Input id="input2" type="text" />
    </div>
    <div class="flex">
      <Label for="input3">Page width: </Label>
      <Input id="input3" type="text" />
    </div>
    
    <div class="flex">
      <Label for="input4">Input 4: </Label>
      <Input id="input4" type="text" />
    </div>
    <div class="flex">
      <Label for="input5">Input 5: </Label>
      <Input id="input5" type="text" />
    </div>
    <div class="flex">
      <Label for="input6">Input 6: </Label>
      <Input id="input6" type="text" />
    </div>
</div>

  
    
</template>

<style scoped>
.item {
  margin-top: 2rem;
  display: flex;
  position: relative;
}

.details {
  flex: 1;
  margin-left: 1rem;
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;

  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}
</style>
