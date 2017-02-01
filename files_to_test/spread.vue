<template>
    <ul>
        <li>some</li>
        <li>another</li>
    </ul>
</template>
<script>
const foo = {
  bar: 'bar'
}

const baz = {
  ...foo,
  bar2: 'bar2'
}

console.log('foo', foo)
console.log('baz', baz)
</script>
