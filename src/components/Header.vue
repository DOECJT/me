<script setup lang="ts">
import { Console } from 'console'

const websiteName = 'doecjt'
const a = 'test'
const b = false

function foo() {
  if (b)
    return
  debugger
  if (a)
    console.log('a', a)

  Console.log('hello')
}
</script>

<template>
  <div>
    <div>{{ websiteName }}</div>
    <div />
  </div>
</template>
