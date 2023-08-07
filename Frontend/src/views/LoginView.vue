<template>
  <nav class="py-10 px-8 border-b border-gray-200">
      <div class="max-w-7xl mx-auto">
          <div class="flex items-center justify-between">
              <div class="menu-left"> <a> Social Media </a></div>
              <div class="menu-right">
                  <a href="#" class="py-4 px-6 bg-gray-600 text-white rounded-lg">Log in</a>
                  <a href="#" class="py-4 px-6 bg-pink-600 text-white rounded-lg">Sign up</a>
              </div>
          </div>
      </div>
  </nav>
  <main class="px-8 py-6 bg-gray-100">
   <div class="max-w-7xl mx-auto grid grid-cols-4 gap-4"> 
   
    <div class="main-left col-span-2">
        <div class="p-12 bg-white border border-gray-200 rounded-lg">
          <h1> Log In </h1>
          <br>
          <div>
          <p> Lorem ipsum jun bunny hold beyonce what the frog ginger tea cos push no kirb.Lorem ipsum jun bunny hold beyonce what the frog ginger tea cos push no kirb </p>
          </div>
          <br>
          <b> Dont have an account? <RouterLink to="/signup" class="underline"> Click here </RouterLink> to create one </b> 
        </div>
     </div>
     <div class="main-centre col-span-2 space-y-4">
        <div class="p-12 bg-white border border-gray-200 rounded-lg">
           <form class="space-y-6">
          
             <div>
                Email
                 <input type="email" placeholder="Your e-mail address" class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
              </div>
              <br>
              <div>
                Password
                 <input type="password" placeholder="Your password" class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
              </div>
              
              <button class="py-4 px-6 bg-pink-600 text-white rounded-lg">Log in</button>
           </form>
         </div>
     </div>
   </div>
 </main>
</template>