<template>
  <div class="app flex-row align-items-center">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-6">
         刷新数据
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Page500',
  ready: function(){
			
		},
		mounted:function(){
		this.Fnnn()
		},
		methods:{
			Fnnn(){
				this.$router.push({
					name:"下注"
				})
			}
		}
}


</script>
