<template>
    <div>
  <div class="w-full lg:px-10 xl:px-20 bg-white p-4 flex items-center justify-between border-b">
           <div class="left-nav flex items-center space-x-3">
               <div class="logo">
                   <img src="~/assets/icons/Logo.svg" alt="" srcset="">
               </div>
               <div class="menu-items lg:block hidden text-gray-500">
                   <ul class="flex items-center list-none space-x-6">
                       <li><nuxt-link to="#">Home</nuxt-link></li>
                       <li class="bg-gray-100 p-2 rounded-md"> <nuxt-link to="#">Dashboard</nuxt-link> </li>
                       <li ><nuxt-link to="#">Projects</nuxt-link> </li>
                       <li> <nuxt-link to="#">Task</nuxt-link> </li>
                       <li> <nuxt-link to="#">Reporting</nuxt-link> </li>
                       <li> <nuxt-link to="#">Users</nuxt-link> </li>
                   </ul>
               </div>
           </div>

           <div class="right-nav  hidden lg:flex items-center space-x-3">
               <button class="flex items-center border px-3 py-1 rounded-md text-gray-500 space-x-3 hover:bg-gray-200 cursor-pointer">
                   <img src="~/assets/icons/zap.svg" alt="" srcset="">
                    <span>Upgrade now</span>
               </button>

              <div class="setting">
                   <img src="~/assets/icons/settings.svg" alt="" srcset="">
            </div>

            <div class="notify-bell">
            <img src="~/assets/icons/bell.svg" alt="" srcset="">
            </div>
             
            <div class="profile border border-black w-10 shadow-full rounded-full">
            <img class="w-10  border rounded-full border-2 " src="~/assets/img/download.jpeg" alt="" srcset="">
            </div>


           </div>

           <div class="mobile-menu lg:hidden">
               <img src="~/assets/icons/harmburger.svg" alt="" srcset="">
           </div>
       </div>

        <div class="w-full lg:px-10 xl:px-20 bg-white p-3 flex items-center justify-between lg:border-b">
           <div class="left-nav flex items-center space-x-3">
               <!-- <div class="logo">
                   <img src="~/assets/icons/Logo.svg" alt="" srcset="">
               </div> -->
               <div class="menu-items lg:block hidden text-gray-500">
                   <ul class="flex items-center list-none space-x-6">
                        <li class="bg-gray-100 p-2 rounded-md"> <nuxt-link to="#">Overview</nuxt-link> </li>
                       <li><nuxt-link to="#">Notifications</nuxt-link></li>
                      
                       <li ><nuxt-link to="#">Analytics</nuxt-link> </li>
                       <li> <nuxt-link to="#">Saved reports</nuxt-link> </li>
                       <li> <nuxt-link to="#">Trade history</nuxt-link> </li>
                       <li> <nuxt-link to="#">User reports</nuxt-link> </li>
                   </ul>
               </div>
           </div>

           <div class="right-nav  hidden lg:flex items-center space-x-3 border px-3 py-2  rounded-md ">
                <img src="~/assets/icons/search.svg" alt="" srcset="">
               <input type="text" placeholder="Search..." class="text-gray-500 appearance: none; focus:outline-none"
               />
                  
            

            


           </div>
       </div>
    </div>
     


</template>

<script>
export default {
    name: 'Navbar'
}
</script>
