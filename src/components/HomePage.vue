<template >
<div >
    <table class="inner-context">
        <tr>
            <td class="left-td" >
                <p  class="lower">  PREMIUM VETERINARY SERVICES FOR ALL PETS AND THEIR OWNERS</p>
        <p class="upper" > WHERE </p>
       <p class="upper" >CARING HAS</p>
       <p class="upper" >NO BOUNDARIES</p>
        <p class = "em"> Animal Doctors International is a full-service veterinary clinic driven by a passion for excellence. We provide compassionate clinical care, state-of-the-art technology and highly-skilled international veterinarians to deliver on our promise of exceptional service and personalised care for your loved pets.</p>
        <p class = "em">Our entire staff are committed to maintaining international standards and treating all animals with loving care in every check-up, procedure or surgery. </p>
       </td>
        <td>
           <img src="F:\pet\pet-vue\src\assets\Untitled.png" class="d-block w-100" alt="...">
          <p ></p>
        </td>
  
           
       </tr>
  
        
</table>
        </div>
</template>
<script>

export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}

</script>
<style scoped>
tr{
  max-width: 1000px;
}
.left-td{
  max-width: 600px;
}
.inner-context{
    margin-left: 150px;
    margin-top: 30px;
  
    
}   
.em{
    font-style: italic;
     font-size: 0.8em ;   
    text-transform: uppercase;
   margin-right:200px;
   
}
.upper{
        font-family: "BarlowCondensed",sans-serif;
    font-size: 50px;
    font-weight: 700;
    line-height: .8;
    position: relative;
    display: block;
    text-transform: uppercase;
 
}
.lower{
   font-size: 0.8em ;   
    text-transform: uppercase;
   margin-right:350px;
  
   

}
</style>