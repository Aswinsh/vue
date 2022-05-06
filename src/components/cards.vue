<template>
  
<div class="row">
  <div class="column">
    <div class="card">
      <h3>Max</h3>
      
      <p>age:30</p>
      <p>TVM</p>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <h3>Card 2</h3>
      <p>Some text</p>
      <p>Some text</p>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <h3>Card 3</h3>
      <p>Some text</p>
      <p>Some text</p>
    </div>
  </div>
   
 </div>



  
</template>

<script>


export default {
  name: 'cards-component',
  props: {
    
  }
}

</script>



<style scoped>
body{

  background-color: #f0eaea;
}


.row{
  display: flex;
   justify-content: space-between;
   
} 


.column{

  
  background-color:white ;
  width: 466px;
  ;

}

.card{


  box-shadow: 5px 10px 18px #888888;
  padding-left: 15px;
  padding-bottom: 10px;
  margin-left: 10px;
}

.card:hover{
color: #5b97c8;
-ms-transform: scale(1.1); 
-webkit-transform: scale(1.1); 
transform: scale(1.1); 

}



</style>