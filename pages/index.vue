<template>
    <div>
        <h1>Hello, {{ username }}!!!</h1>
    </div>
</template>

<script>
import { ref, defineComponent } from '@nuxtjs/composition-api'
export default defineComponent({
    setup() {
        const username = ref('Composition Api User')

        return {
            username
        }
    }
})
</script>
