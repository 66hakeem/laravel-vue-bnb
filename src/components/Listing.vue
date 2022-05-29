<template>
    <div class="container">
        <div class="heading">
            <h1>{{ title }}</h1>
            <p>{{ address }}</p>
        </div>
        <hr>
        <div class="about">
            <h3>About this listing</h3>
            <p>{{ about }}</p>
        </div>
    </div>
</template>

<script>
export default {
    data()  {
        return {
            title: 'My apartment',
            address: '12 My Street, My City, My Country',
            about: 'This is a description of my apartment.'
        }
    }
}
</script>

