<template>
    <div>
        <h1>Exam</h1>
               <p><strong></strong></p>
          <ul v-if="posts && posts.length">
            <li v-for="post of posts">
     
            <p>{{post.data}}</p>
            </li>
         </ul>
       
    </div>
</template>
<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
import axios from 'axios';

export default {
  data() {
    return {
      posts: [],
      errors: []
    }
  },

  // Fetches posts when the component is created.
  created() {
    axios.get('http://localhost:3000/xyz')
    .then(response => {
      // JSON responses are automatically parsed.\
      console.log(response);
      this.posts = response.data
    })
    .catch(e => {
      this.errors.push(e)
    })

  }
}
</script>

<style scoped>

</style>