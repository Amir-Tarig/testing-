<template>
 <div class="nav"> 
    <div class="logo"><h2><span>Restaurant</span>Logo</h2></div> 
    <ul class="navList">
        <li class="navLink">Home</li>
         <li class="navLink">Menu</li>
           <li class="navLink">About</li>
              <li class="navLink">Contact</li>
               
    </ul>
</div>
</template>

<script>
export default {
    data() {
        return{
          
        }
    },
  

}
</script>

<style  scoped>

.nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 10vh;
  
}

h2{
    font-size: 13px;
    color: red;
}

span{
    font-size: 2em;
    color: black;
}

.logo{
    text-align: center;
    width: 50%;

}
.navList{
    width: 50%;
    height: 100%;
    display: flex;
    justify-content: space-around;
    align-items: flex-end;
    list-style: none;
}

</style>