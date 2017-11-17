<template>
  <div>
    <div class="panel panel-default">
      <div class="panel-heading">Example Component</div>
      <div class="panel-body">
        <button flat @click="fetchUser">
          fetch user data
          </button>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
      mounted () {
          console.log('component ready')
      },
      methods: {
        fetchUser () {
          axios.get('/api/user').then(response => {
            console.log(response.data)
          })
        }
      }
    }
</script>
