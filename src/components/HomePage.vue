<script setup>
const details = [
	{
		title: "Organize your team the way you want.",
		content:
			"One who is injured ought not to return the injury, for on no account can it be right to do an injustice; and it is not right to return an injury, or to do evil to any man, however much we have suffered from him.",
		image: {
			src: "/Page 24-1.png",
			width: 650,
			height: 550,
		},
	
	},
  {
		title: "Organize your team the way you want.",
		content:
			"One who is injured ought not to return the injury, for on no account can it be right to do an injustice; and it is not right to return an injury, or to do evil to any man, however much we have suffered from him.",
		image: {
			src: "/Page 16.png",
			width: 650,
			height: 550,
		},
	
	},
  {
		title: "Organize your team the way you want.",
		content:
			"One who is injured ought not to return the injury, for on no account can it be right to do an injustice; and it is not right to return an injury, or to do evil to any man, however much we have suffered from him.",
		image: {
			src: "/Page 18.png",
			width: 650,
			height: 550,
		},
	
	},
	{
		title: "Organize your team the way you want.",
		content:
			"One who is injured ought not to return the injury, for on no account can it be right to do an injustice; and it is not right to return an injury, or to do evil to any man, however much we have suffered from him.",
		image: {
			src: "/Page 20.png",
			height: 550,
		},
	
	},
]

</script>
  <template>
  
  <div v-for="(item, index) in details" :key="index" class="group bg-[#1E1E1E] py-12 first:pt-0 last:pb-0 even:bg-light lg:py-20 md:py-16">
  <div class="container mx-auto">
	<div className="block items-center group-even:flex-row-reverse md:space-y-10 lg:m-0 lg:flex lg:space-y-16 xl:mx-10">
              <div className="mx-16 mb-10 text-start lg:m-0 lg:w-full xl:mx-10">
                
                <div className="my-6 text-xl text-white font-semibold tracking-wider md:mb-6 md:text-2xl">
                  {{item.title}}
                </div>
                <div className="tracking-wider text-gray-300 md:text-sm">{{item.content}}</div>
              </div>
              <img
                className="min-w-xs mb-4 mx-10 max-w-md lg:max-w-2xl lg:w-full"
                :src=item.image.src
                :width=item.image.width
                :height=item.image.height
                alt=""
              />
            </div>
   		 </div>
  </div>


</template>

<style scoped>

</style>
