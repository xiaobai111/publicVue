 <template>
  <div class="rating_page">
        <head-top head-title="新增地址" go-back='true'></head-top>
        <section>
        	<form action="">
        		<section class="ui-padding-block">
        			<input type="text">
        		</section>
        	</form>
        </section>
    </div>
</template>

<script>
    import headTop from '../../../../../components/header/head'
    import {getImgPath} from '../../../../../components/common/mixin'

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
    @import '../../../../../style/mixin';
  
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
    .ui-padding-block{
    	background:#fff;
    }
</style>
