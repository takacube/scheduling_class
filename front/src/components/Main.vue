<template>
    <div id="task">
        <ul>
            <li><h3>電気数学</h3></li>
            <li>3回目</li>
            <li>復習日一覧:</li>
        </ul> 
        <button>完了</button>
    </div>
</template>

<script>
export default {
  name: 'Main',

  // 親コンポーネントから受け取るpropsを定義しています。
  // 定義方法はいろいろありますが、ここでは一番シンプルに
  // 配列でプロパティ名を書いています。
  props: ['name', 'price'],
};
</script>
<style scoped>
    * {
    list-style: none;
    }

    #task {
        background-color: beige;
        width: 500px;
        margin: auto;
    }

    #task ul {
        text-align: center;
    }
</style>





<!--
<template>
        <section class="alert alert-primary">
        <h1>{{data.title}}</h1>
        <p>{{data.message}}</p>
        <p>{{data}}</p>
        <textarea v-model="data.mydata" rows="5" class="form-control"></textarea>
        </section>
    
</template>
-->
<!--
<script>








    /*import axios from 'axios'
    import  { reactive, onMounted } from 'vue'
    const url = "/data.txt"
    export default {
        setup(props) {
            const data = reactive({
                title: 'Axios',
                message: 'This is axios ssample',
                mydata: '',
            })
            const getData = async() => {
                let result = await axios.get(url)
                data.mydata = result.data
            }
            onMounted(()=> {
                getData()
            })
            return { data, getData }
        }
    }
    */
</script>
-->
