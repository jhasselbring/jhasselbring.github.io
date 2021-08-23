<template>
  <div class="bg-gray-900 text-white flex">
    <div class="flex-initial bg-gray-800" >
      <pre>
     1&nbsp;
     2&nbsp;
     3&nbsp;
     4&nbsp;
     5&nbsp;
     6&nbsp;
     7&nbsp;
     8&nbsp;
     9&nbsp;
    10&nbsp;
    11&nbsp;
    12&nbsp;
    13&nbsp;
      </pre>
    </div>
    <div class="flex-1" style="box-shadow: inset 0 0 15px rgba(0,0,0,0.5);">
          <pre>
    <span class="green">
      /**
       * Just something nerdy to look at
       * ToDo: Add more geeky stuff later
       */</span>
      <span class="orange">const</span> <span class="yellow">Jan</span> = () => {
        <span class="orange">return</span> {
              <span class="purple">fullName</span>: <span class="green">"Jan Mykhail Hasselbring"</span><span class="orange">,</span>
              <span class="purple">nickName</span>: <span class="green">"Jay"</span><span class="orange">,</span>
              <span class="purple">email</span>: <span class="green">"janmykhail.hasselbring@outlook.com"</span><span class="orange">,</span>
              <span class="purple">phone</span>: <span class="green">"224-637-5331"</span>
          }
      }
    </pre>

    </div>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
.orange{
  @apply text-yellow-500;
}
.yellow{
 @apply text-yellow-300;
}
.purple{
  @apply text-purple-500;
}
.green{
  @apply text-green-500;
}
</style>
