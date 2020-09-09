0.<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <input type="text" v-model="message">
    <p>{{message}}</p>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: ['msg'],
  data(){
    return{
      message:''
    }
  }
 
}
  
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
