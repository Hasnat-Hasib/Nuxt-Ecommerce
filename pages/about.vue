<script setup>
     // const { data } = await useFetch('/api/ninja?name=mario')
  // const { data } = await useFetch('/api/ninja?name=mario', {
  //   method: 'post',
  //   body: {age: 30}
  // })
  const { data } = await useFetch('/api/currency/BDT')

</script>

<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, molestiae. Ipsa, fugiat. Incidunt perspiciatis rem similique voluptates est voluptatum totam adipisci a odit ipsam quas, aliquid tempora accusamus doloribus dicta?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, molestiae. Ipsa, fugiat. Incidunt perspiciatis rem similique voluptates est voluptatum totam adipisci a odit ipsam quas, aliquid tempora accusamus doloribus dicta?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, molestiae. Ipsa, fugiat. Incidunt perspiciatis rem similique voluptates est voluptatum totam adipisci a odit ipsam quas, aliquid tempora accusamus doloribus dicta?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, molestiae. Ipsa, fugiat. Incidunt perspiciatis rem similique voluptates est voluptatum totam adipisci a odit ipsam quas, aliquid tempora accusamus doloribus dicta?
        </p>
        <div>{{ data }}</div>
        
    </div>
</template>

<style scoped>
h2{
    margin-bottom: 20px;
    font-size: 36px;
}
p{
    margin: 20px 0;
}

</style>