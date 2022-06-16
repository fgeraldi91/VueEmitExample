<script>
  export default {
    name: 'ComponenteFilho',
    props: {
      msg: String
    },
    methods:{
      passEvent()
      {
          this.$emit('textoComponenteFilho','Texto vindo do componente filho')
      }
    },
    created: function(){
      this.passEvent()
    }
  }
</script>