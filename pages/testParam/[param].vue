<template>
    /test param [param] 
    <div style="height:500px;">
      {{$route.params.param || 'no param'}}
    </div>
</template>