<template>
<div>
  <!-- this is the navbar component  -->
    <Navbar/>

  <div>
  <!-- main layout -->
    <div class="lg:px-10 xl:px-20 lg:py-10 px-4">
      
      <div class="welcome grid lg:grid-cols-2 gap-4">
        <div class="welcome" >
           <h1 class="text-2xl">Welcome back, Prince</h1>
           <p  class="text-xs text-gray-500">Track, manage and forecast your customers and orders.</p>
   
        </div>
       
       <div class="buttons space-x-3 flex item-center lg:justify-self-end">
          <button class="flex items-center border px-3 py-1 rounded-md text-gray-500 space-x-3 hover:bg-gray-200 cursor-pointer text-sm">
                   <img src="~/assets/icons/import.svg" alt="" srcset="">
                    <span>Import</span>
               </button>

              <button class="flex items-center text-white px-3 py-1 rounded-md space-x-3 bg-purple-500 text-sm">
                   <img src="~/assets/icons/add.svg" alt="" srcset="">
                    <span>Add</span>
               </button>  
       </div>
      </div>

     

      <div class="cards my-10 grid lg:grid-cols-3 gap-4">
        <div class="card-item p-4 border shadow-md space-y-4 rounded-md">
          <div class=" flex items-center justify-between">
            <h3>Total customers</h3>
            <img class="cursor-pointer" src="~/assets/icons/3-dots.svg" alt="" srcset="">
          </div>

          <div class="flex items-center justify-between">
            <div class="space-y-3">
               <h1 class="text-3xl font-bold">2,420</h1>

               <div class="flex items-center space-x-2 text-sm">
                 <img src="~/assets/icons/arrow-up.svg" alt="" srcset="">
                 <span class="text-green-500">40%</span>
                 <span class="text-gray-500">vs last month</span>
               </div>
            </div>
            <div class="line-curve">
              <img src="~/assets/icons/green-line.svg" alt="" srcset="">
            </div>


           
          </div>


        </div>


         <div class="card-item p-4 border shadow-md space-y-4 rounded-md">
          <div class=" flex items-center justify-between">
            <h3>Members</h3>
            <img class="cursor-pointer" src="~/assets/icons/3-dots.svg" alt="" srcset="">
          </div>

          <div class="flex items-center justify-between">
            <div class="space-y-3">
               <h1 class="text-3xl font-bold">1,210</h1>

               <div class="flex items-center space-x-2 text-sm">
                 <img src="~/assets/icons/arrow-down.svg" alt="" srcset="">
                 <span class="text-red-500">10%</span>
                 <span class="text-gray-500">vs last month</span>
               </div>
            </div>
            <div class="line-curve">
              <img src="~/assets/icons/red-line.svg" alt="" srcset="">
            </div>


           
          </div>


        </div>

           <div class="card-item p-4 border shadow-md space-y-4 rounded-md">
          <div class=" flex items-center justify-between">
            <h3>Active now</h3>
            <img class="cursor-pointer" src="~/assets/icons/3-dots.svg" alt="" srcset="">
          </div>

          <div class="flex items-center justify-between">
            <div class="space-y-3">
               <h1 class="text-3xl font-bold">316</h1>

               <div class="flex items-center space-x-2 text-sm">
                 <img src="~/assets/icons/arrow-up.svg" alt="" srcset="">
                 <span class="text-green-500">20%</span>
                 <span class="text-gray-500">vs last month</span>
               </div>
            </div>
            <div class="line-curve">
              <img src="~/assets/icons/green-line.svg" alt="" srcset="">
            </div>


           
          </div>


        </div>



      </div>


      <section>
        <div class="filter w-full flex flex-col flex-col-reverse lg:flex-row items-center gap-3 my-10">

                 <div class="flex items-center lg:flex-row flex-col flex-col-reverse gap-2 w-full">


                 <div class="buttons flex-wrap flex items-center gap-2 lg:w-1/4 w-full">
                  <button class="flex  items-center justify-center text-white px-3 py-2 rounded-md space-x-2 bg-purple-200 text-xs text-purple-600">
                  
                    <span>All time</span>
                     <img src="~/assets/icons/cancel.svg" alt="" srcset="">
               </button> 

                <button class="flex items-center justify-center  text-white px-3 py-2 rounded-md space-x-2 bg-purple-200 text-xs text-purple-600">
                  
                    <span>US, AU, +4</span>
                     <img src="~/assets/icons/cancel.svg" alt="" srcset="">
               </button>  
               
               
              
                </div>

                <div class="more-filter lg:w-1/4 w-full">
                   <button class=" w-full flex border items-center justify-center text-gray-500 px-3 py-2 rounded-md space-x-2 text-xs">
                   <img src="~/assets/icons/filter.svg" alt="" srcset="">
                    <span>More filters</span>
               </button>  
                </div>
                 </div>
              
               


                <div class="search flex items-center space-x-3 border px-3 py-2  rounded-md ml-auto lg:w-1/4 w-full ">
                <img src="~/assets/icons/search.svg" alt="" srcset="">
               <input type="text" placeholder="Search..." class="text-gray-500 appearance: none; focus:outline-none text-sm"
               />
                  
            

            


           </div> 

        </div>

        <div class="data-table overflow-x-auto shadow-md">
        <div class=" flex items-center justify-center overflow-x-auto border rounded-md" >
            <div class="w-full">
              
                    <table class="min-w-max w-full table-auto">
                        <thead>
                            <tr class="text-gray-500  text-xs">
                               <th class="py-3 px-6 text-left flex items-center gap-2">
                                 <img class="w-4" src="~/assets/icons/Checkbox.svg" alt="" srcset="">
                              <span>Company</span>
                              <img src="~/assets/icons/arrow-gray-down.svg" alt="" srcset="">

                               </th>
                                <th class="py-3 px-6 text-left">Licence Use</th>
                                <th class="py-3 px-6 text-left">Status</th>
                                <th class="py-3 px-6 text-left">Users</th>
                                <th class="py-3 px-6 text-left">About</th>
                                  <th class="py-3 px-6 text-left"></th>
                                
                            </tr>
                        </thead>

                        <tbody class="text-gray-600 text-sm font-light">
                            <tr class="border-b border-gray-200 bg-gray-100 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="" class="ring-red-500" checked>
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/catalogue.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Catalog</span>
                                           <p class="text-xs">catalogapp.io</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-2/3 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-green-100 text-green-700 py-1 px-3 rounded-full text-xs">Customer</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +5
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Content curating app</h1>
                                  <p  class="text-xs text-gray-500">Brings all your news into one place</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                               <tr class="border-b border-gray-200 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/circlooes.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Circooles</span>
                                           <p class="text-xs">getcirooles.com</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-1/3 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-gray-200 text-gray-700 py-1 px-3 rounded-full text-xs">Churned</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +8
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Design software</h1>
                                  <p  class="text-xs text-gray-500">Super lightweight design app</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                             <tr class="border-b border-gray-200 bg-gray-100 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/command.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Command+R</span>
                                           <p class="text-xs">cmdr.ai</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-1/4 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-green-100 text-green-700 py-1 px-3 rounded-full text-xs">Customer</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +2
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark"> Data prediction</h1>
                                  <p  class="text-xs text-gray-500">AI and machine learning data</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                               <tr class="border-b border-gray-200 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/hour.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Hourglass</span>
                                           <p class="text-xs">hourglass.app</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-2/3 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-green-100 text-green-700 py-1 px-3 rounded-full text-xs">Customer</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <!-- <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +5
                                        </span> -->
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Productivity app</h1>
                                  <p  class="text-xs text-gray-500">Time management and productivity</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                             <tr class="border-b border-gray-200 bg-gray-100 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/layer.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Layers</span>
                                           <p class="text-xs">getlayers.io</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-1/5 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-gray-200 text-gray-700 py-1 px-3 rounded-full text-xs">Churned</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +1
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Web app integrations</h1>
                                  <p  class="text-xs text-gray-500">Connect web apps seamlessly</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                               <tr class="border-b border-gray-200 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/quotient.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Quotient</span>
                                           <p class="text-xs">quotient.co</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-10 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-green-100 text-green-700 py-1 px-3 rounded-full text-xs">Customer</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +6
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Sales CRM</h1>
                                  <p  class="text-xs text-gray-500">Web-based sales doc management</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                             <tr class="border-b border-gray-200 bg-gray-100 ">
                                <td class="py-3 px-6 text-left whitespace-nowrap">
                                    <div class="flex items-center gap-2">
                                      <input type="checkbox" name="" id="">
                                        <div class="">
                                          <img class="w-8" src="~/assets/icons/sisyphus.svg" alt="" srcset="">
                                        </div>

                                        <div>
                                           <span class="font-medium">Sisyphus</span>
                                           <p class="text-xs">sisyphus.com</p>
                                        </div>
                                       
                                    </div>
                                </td>

                                <td class="py-3 px-6 text-left">
                                    <div class="w-full h-2 bg-purple-200 rounded-full">
                                <div class="w-20 h-full text-center text-xs text-white bg-purple-600 rounded-full">
                                  </div>
                               </div>
                                </td>

                                  <td class="py-3 px-6 text-left">
                                    <span class="bg-green-100 text-green-700 py-1 px-3 rounded-full text-xs">Customer</span>
                                </td>

                                <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/3.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 transform hover:scale-125" src="https://randomuser.me/api/portraits/men/1.jpg"/>
                                        <img class="w-6 h-6 rounded-full border-white border-2 -m-1 transform hover:scale-125" src="https://randomuser.me/api/portraits/women/2.jpg"/>

                                        <span class="w-6 h-6 text-xs text-purple-500 bg-purple-100
                                        border-white border-2  rounded-full flex justify-center items-center -m-1 transform hover:scale-125">
                                          +4
                                        </span>
                                    </div>
                                </td>
                               
                               
                                <td class="class py-3 px-6 text-left">
                                  <h1 class="text-dark">Automation and workflow</h1>
                                  <p  class="text-xs text-gray-500">Time tracking, invoicing and expenses</p>
                                </td>

                                 <td class="py-3 px-6 text-center">
                                    <div class="flex items-center justify-center">
                                       
                                        <div class=" mr-2">
                                           <img src="~/assets/icons/delete.svg" alt="" srcset="">
                                        </div>
                                        <div class="mr-2">
                                            
                                            <img src="~/assets/icons/edit.svg" alt="" srcset="">
                                        </div>
                                    </div>
                                </td>
                            </tr>

                            
                        </tbody>

                        
                           
                    </table>

                    <div class="pagination lg:flex hidden items-center justify-between p-3">
                      <div class="buttons flex items-center gap-2">
                         <button class="flex items-center border px-3 py-1 rounded-md text-gray-500 space-x-3 hover:bg-gray-200 cursor-pointer">
                  
                    Previous
               </button>

                <button class="flex items-center border px-3 py-1 rounded-md text-gray-500 space-x-3 hover:bg-gray-200 cursor-pointer">
                  
                    Next
               </button>
                      </div>

                      <span class="text-xs text-gray-500">Page 1 of 10</span>
                    </div>
              
            </div>

        </div>
    </div>

     <div class="mobile-pagination flex lg:hidden items-center justify-between p-3 border-t my-4">
                
                 <button>
                  
                 <img src="~/assets/icons/arrow-left.svg" alt="" srcset="">
               </button>
                   <span class="text-xs text-gray-500">Page 1 of 10</span>
                <button>
                  
                 <img src="~/assets/icons/arrow-right.svg" alt="" srcset="">
               </button>
                    

                     
                    </div>


      </section>
    
      
      
      </div>
  </div>


</div>



</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
