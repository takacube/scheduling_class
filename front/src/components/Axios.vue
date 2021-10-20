<template>
  <div>
      <p>{{posts}}</p>
      <p>{{posts}}</p>
      <p>{{postman['content-length']}}</p>
  </div>
</template>
<script>
    import axios from 'axios' //追記
    export default {
        data(){
            return {
            posts: [],
            postman: [],
            post_content: []
            }
        },
        created() {
            this.test(),
            this.test2(),
            this.test_post()
        },
        methods: {
            test: function(){
            axios.get('https://httpbin.org/get').then(res=>{
                console.log(res)
                this.posts = res.headers
            }).catch(err=>{
                console.log(err)
            })
            },

            test2: function(){
            axios.get('https://httpbin.org/get').then(res=>{
                console.log(res)
                this.postman = res.headers
            }).catch(err=>{
                console.log(err)
            })
            },
            test_post: function(){
            axios.post('', headers).then(res=>{
                this.post_content = res
            })
            }
        }
    }
</script>