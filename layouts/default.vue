<template>
    <div>
        <header class="flex justify-between mx-20 my-20 ">
<div>logo</div>
    
      <div class="flex justify-normal">
        <div class="btn"> <button><NuxtLink to="/">home</NuxtLink></button></div>
        <div class="btn"><button><NuxtLink to="/about">about</NuxtLink></button></div>
        <div class="btn"><button><NuxtLink to="/products" >products </NuxtLink> </button></div>
        
      </div>
    </header>
    </div>
    <div>
        <slot />
    </div>
</template>
