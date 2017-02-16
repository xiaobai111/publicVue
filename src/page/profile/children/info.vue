 <template>
  <div class="rating_page">
        <head-top head-title="账户信息" go-back='true'></head-top>
        <section class="headportrait">
            <h2>头像</h2>
            <div>
                <span></span>
                <span></span>
            </div>
        </section>

    </div>
</template>

<script>
    import headTop from '../../../components/header/head'
    import {getImgPath} from '../../../components/common/mixin'

    export default {
      data(){
            return{
    
            }
        },
        created(){

        },
        mixins: [getImgPath],
        components: {
            headTop,

        },
        props:[],
        methods: {
            
        }
    }
</script>
  
<style lang="scss" scoped>
    @import '../../../style/mixin.scss';
  
    .rating_page{
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: #f2f2f2;
        z-index: 202;
        padding-top: 1.95rem;
        p, span{
            font-family: Helvetica Neue,Tahoma,Arial;
        }
    }
    
</style>
