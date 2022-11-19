<template>
    <div>
        <h1>a single user, with id: {{ $route.params.id }}</h1>
        <nuxt-link to="/">back menu</nuxt-link><br>
        <nuxt-link to="/users">back users</nuxt-link>
        <nuxt-link to="/users/more-detail">more-detail</nuxt-link>
    </div>
</template>

<script>
// export default {
//    validate(data) {
//     return /^\d+$/.test(data.params.id) 
//    } 
// }
export default{
    layout: 'users'
}

</script>