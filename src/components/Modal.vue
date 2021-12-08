<template>
    <div class="backdrop">
        <div class="modal">
            <h1>{{ header }}</h1>
            <p>Modal component</p>
        </div>
    </div>
</template>
<script>
    export default { 
        props: ['header']
    }
</script>
