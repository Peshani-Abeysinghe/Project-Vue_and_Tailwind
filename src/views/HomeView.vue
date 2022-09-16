<template>
 
   <nav 
     role="navigation"
     class="flex flex-wrap items-center text-base justify-center h-24 bg-gray-900 text-white  sticky top-0 z-50 ">
   
     <img class=" w-45 h-20" src="../assets/Moonbeam-Logo-Final-500px.png">
    
   
    <div class="px-4 cursor-pointer" id="bars"></div>
    

      

      <a href="#" class="p-4 mr-5 hidden">Builders </a>
       <a href="#" class="p-4 mr-5">Community</a>
      <a href="#" class="p-4 mr-5">Networks</a>
      <a href="#" class="p-4 mr-5">Tokens</a>
      <a href="#" class="p-4 mr-5">About</a>

      <button class="border border-white text-white  duration-500 px-6 py-2 mx-4 hover:border-pink-800 hover:text-pink-800 rounded">
        Foundation
      </button>

      <button class="bg-pink-600 text-white  duration-500 px-6 py-2 mx-4 hover:bg-pink-800 rounded href=About.vue"><router-link to="/about">
        Launch App</router-link>
      </button>

      <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">

      <svg class="  http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"  viewBox="0 0 16 16">
        <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
      </svg>
     </a>

     <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-300 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce " aria-label="Github">

      <svg class=" http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"  viewBox="0 0 16 16">
        <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z"/>
      </svg>

      </a>

      <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-300 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce" aria-label="Github">

      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
        <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
      </svg>
      </a>

      <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-300 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce" aria-label="Github">

      <svg class="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"  viewBox="0 0 16 16">
        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.287 5.906c-.778.324-2.334.994-4.666 2.01-.378.15-.577.298-.595.442-.03.243.275.339.69.47l.175.055c.408.133.958.288 1.243.294.26.006.549-.1.868-.32 2.179-1.471 3.304-2.214 3.374-2.23.05-.012.12-.026.166.016.047.041.042.12.037.141-.03.129-1.227 1.241-1.846 1.817-.193.18-.33.307-.358.336a8.154 8.154 0 0 1-.188.186c-.38.366-.664.64.015 1.088.327.216.589.393.85.571.284.194.568.387.936.629.093.06.183.125.27.187.331.236.63.448.997.414.214-.02.435-.22.547-.82.265-1.417.786-4.486.906-5.751a1.426 1.426 0 0 0-.013-.315.337.337 0 0 0-.114-.217.526.526 0 0 0-.31-.093c-.3.005-.763.166-2.984 1.09z"/>
      </svg>
    </a>


    <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-300 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce" aria-label="Github">

        <svg class="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"  viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.502.502 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103zM10 1.91l-4-.8v12.98l4 .8V1.91zm1 12.98 4-.8V1.11l-4 .8v12.98zm-6-.8V1.11l-4 .8v12.98l4-.8z"/>
            </svg>
          </a>

          <a href="#" class="mx-2 text-gray-600 transition-colors duration-200 transform dark:text-gray-300 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce" aria-label="Github">

            <svg class="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"  viewBox="0 0 16 16">
              <path d="M13.545 2.907a13.227 13.227 0 0 0-3.257-1.011.05.05 0 0 0-.052.025c-.141.25-.297.577-.406.833a12.19 12.19 0 0 0-3.658 0 8.258 8.258 0 0 0-.412-.833.051.051 0 0 0-.052-.025c-1.125.194-2.22.534-3.257 1.011a.041.041 0 0 0-.021.018C.356 6.024-.213 9.047.066 12.032c.001.014.01.028.021.037a13.276 13.276 0 0 0 3.995 2.02.05.05 0 0 0 .056-.019c.308-.42.582-.863.818-1.329a.05.05 0 0 0-.01-.059.051.051 0 0 0-.018-.011 8.875 8.875 0 0 1-1.248-.595.05.05 0 0 1-.02-.066.051.051 0 0 1 .015-.019c.084-.063.168-.129.248-.195a.05.05 0 0 1 .051-.007c2.619 1.196 5.454 1.196 8.041 0a.052.052 0 0 1 .053.007c.08.066.164.132.248.195a.051.051 0 0 1-.004.085 8.254 8.254 0 0 1-1.249.594.05.05 0 0 0-.03.03.052.052 0 0 0 .003.041c.24.465.515.909.817 1.329a.05.05 0 0 0 .056.019 13.235 13.235 0 0 0 4.001-2.02.049.049 0 0 0 .021-.037c.334-3.451-.559-6.449-2.366-9.106a.034.034 0 0 0-.02-.019Zm-8.198 7.307c-.789 0-1.438-.724-1.438-1.612 0-.889.637-1.613 1.438-1.613.807 0 1.45.73 1.438 1.613 0 .888-.637 1.612-1.438 1.612Zm5.316 0c-.788 0-1.438-.724-1.438-1.612 0-.889.637-1.613 1.438-1.613.807 0 1.451.73 1.438 1.613 0 .888-.631 1.612-1.438 1.612Z"/>
            </svg>

          </a>
         

       
   
  </nav>
     
<!-- Section 1 Hero Section-->


<section class=" text-white body-font bg-gradient-to-r from-black to- bg-purple-900">
    <div class="container mx-auto flex px-5 py-10 md:flex-row flex-col items-center">
      <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h1 class="title-font sm:text-5xl text-4xl mb-4 font-medium text-white font-sans px-16 ">The Future is
          <h1 class="title-font sm:text-5xl text-3xl mb-4 font-medium text-white font-sans underline decoration-pink-700 px-16  ">Multi-Chain</h1>
          
        </h1>
        <p class="mb-8 leading-relaxed py-10 px-16">Expand to new chains. Powered by <br> Moonbeam, an Ethereum- compatible<br> smart contract parachain on <br> Polkadot</p>
        

      </div>
      <div class="auto">
        <img class="object-cover object-center rounded" alt="hero" src="../assets/futuristic-urban-cityscape-moonbeam-2.png">
      </div>
    </div>
  </section>







  <!--section 2 Multichain-->


<section class="text-white body-font bg-gray-900">
    <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col ">

      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 ">
     <img class="object-cover object-center rounded" alt="hero" src="../assets/Moon-Buggy-full-rotation.gif">


      </div>

      <div class="lg:flex-grow md:w-1/2 lg:pl-10 md:pl-16 flex flex-col    ">
        <h1 class="title-font sm:text-4xl text-3xl  font-medium text-white  px-0 mt-0">The Easiest Path to Multi-Chain
          
        </h1>


        <div class="mt-8 grid lg:grid-cols-2 gap-8 ">
          


          <div><h2 class="title-font font-medium text-lg text-white mt-3 ">Minimal configuration changes</h2> 

            <h3 class="text-gray-400 mt-5">No need to rewrite or recognfigure your smart <br> contracts. They'll work right away.</h3>


          </div>

<div><h2 class="title-font font-medium text-lg text-white mt-5  ">Tools You Already Use</h2> 
  
            <h3 class="text-gray-400 mt-5 ">Use Ethereum-based tools you like<br>MetaMask, Remix, Hardhat, Waffle, and <br> Truffle</h3></div>

          <div><h2 class="title-font font-medium text-lg text-white mt-5">Familier Smart Contract Languages</h2> 
    
            <h3 class="text-gray-400 mt-5 ">Support for Solidity, Vyper, and anything that<br>complies to EVM bytecode.</h3>
</div>


<div> <h2 class="title-font font-medium text-lg text-white mt-5  ">Pre-Built Integrations</h2> 
      
            <h3 class="text-gray-400 mt-5 ">Built-in integrations for assets like DOT and<br> ERC-20s, and infrastructure services like<br> Chainlink and The Graph.</h3>

</div>
  
  </div>





      </div>

    </div>
    </section>




<!--section 3 Ethereum-->


  <section class="text-gray-900 body-font bg-gray-100">
    <div class="container px-5 py-12 mx-auto text-center font-sans">


 <h2 class="title-font font-medium text-5xl text-gray-900 mt-14  ">A FullyEthereum-Compatible <br>
          Environment on Polkadot</h2> 

       <p class="text-xl text-gray-900 mt-12">Moonbeam is much more than just an EVM implementation: it's a highly specialized Layer 1 chain that mirrors <br> Ethereum's Web3 RPC, accounts, keys, subscriptions, logs, and more. The Moonbeam platform extends the<br> base Ethereum feature set with additional features such as on-chain governance, staking, and cross-chain <br> integrations.</p>


<a class="mt-6 text-pink-600 inline-flex items-center">Documentation
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </a>
          <br>


        <a class="mt-6 text-pink-600 inline-flex items-center">GitHub Repo
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
            </svg>
      </a>

    </div>


     <div class="mt-24 pb-8 px-64 grid lg:grid-cols-3 gap-5">
   
         <div><h2 class="title-font font-medium text-xl text-gray-900 mt-3 text-right ">Solidity Smart Contracts</h2> 

          <h3 class="text-gray-900 mt-5 text-base text-right">Re-deploy your existing smart <br> contracts to a Polkadot <br>environment without the <br>need to refactor or rewrite.</h3>

         </div>


<div></div>
         <div><h2 class="title-font font-medium text-xl text-gray-900 mt-3 text-left ">Publish-Subscribe Capabilities</h2> 

          <h3 class="text-gray-900 mt-5 text-base text-leftt">Subscribe to contract events <br> and updates about on-chain <br> transactions, balances, and <br> more.</h3></div>
         <div></div>
         <div><img class=" object-center " alt="hero" src="../assets/rotating-ethereum-logo.gif"></div>
         <div></div>
         <div><h2 class="title-font font-medium text-xl text-gray-900 mt-3 text-right ">H160 Accounts & ECDSA <br> Signatures</h2> 

          <h3 class="text-gray-900 mt-5 text-base text-right">Interact with Moonbeam <br>using your existing Ethereum <br>accounts and keys.</h3></div>
        <div></div>
        <div><h2 class="title-font font-medium text-xl text-gray-900 mt-3 text-left ">Complete Set of Web3 RPC <br> Endpoints</h2> 

          <h3 class="text-gray-900 mt-5 text-base text-left">Connect existing tools and <br> dApp front-ends to <br> Moonbeam like you would to <br> Ethereum.</h3></div>




    </div>
  </section>




  <!--section 4 Polkadot-->


<section class="text-white body-font bg-black">
    <div class="container px-36 py-24 mx-auto">

      <div class="p-4 flex flex-col  items-center">
       
          <img class=" mx-auto object-center  " alt="hero" src="../assets/Polkadot_Logotype_white-pink-300x150.png">

        </div>


      <div class="text-center mb-20">
        <h1 class="sm:text-5xl font-medium title-font text-white mb-4 "> Grow Your Project with Multi-Chain</h1>
        <p class=" leading-relaxed text-2xl  mx-auto text-gray-500s">Moonbeam helps projects expand their reach to new users and <br> markets with a multi-chain approach.</p>
    
      </div>
      
      <div class="flex  sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6">
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class=" inline-flex items-center justify-center   text-white mb-5 ">
            
            <img class=" mx-auto  " alt="hero" src="../assets/user-100.png">


          </div>


          <div class="flex-grow">
            <h2 class="text-white text-lg title-font font-medium mb-3">New Users and Use Cases</h2>
            <p class="leading-relaxed text-base">Address segments of your market that are out <br> of reach on Ethereum due to gas prices.</p>
            
          </div>
        </div>


        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class="w-20 h-20 inline-flex items-center justify-center   text-white mb-5 flex-shrink-0">
            <img class=" mx-auto  " alt="hero" src="../assets/coins-100.png">

          </div>




          <div class="flex-grow">
            <h2 class="text-white text-lg title-font font-medium mb-3">Rich Pool of Assets</h2>
            <p class="leading-relaxed text-base">Gain immediate access to DOT, KSM, native <br> Polkadot assets like GLMR and aUSD, plus <br> other bridged assets such as Bitcoin and <br> Ethereum-based ERC-20s.</p>
            
          </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <div class="w-20 h-20 inline-flex items-center justify-center   text-white mb-5 flex-shrink-0">
            <img class=" mx-auto  " alt="hero" src="../assets/expansion-100.png">


          </div>
          <div class="flex-grow">
            <h2 class="text-white text-lg title-font font-medium mb-3">Growing Ecosystem</h2>
            <p class="leading-relaxed text-base">Enjoy a “first mover” advantage by deploying  <br>early to Polkadot's rapidly expanding <br> parachain ecosystem.</p>
            
          </div>
        </div>
      </div>
     
    </div>
  </section>





<!--section 5 Smart Contract-->

<section class="text-white body-font  bg-black">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col "> 
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 px-20">
      <img class="object-cover object-center rounded" alt="hero" src="../assets/Glimmer-100.png">


     
        <h1 class="title-font sm:text-4xl text-3xl  font-medium text-white  px-0 mt-5">Smart Contracts, <br> Powered by the <br> Glimmer Token
          
        </h1>
        <h3 class="text-white mt-5">As a decentralized smart contract platform,<br> Moonbeam requires a utility token to function. <br> Our token, Glimmer (GLMR), is central to the <br> design of the network and can’t be removed <br> without sacrificing security and essential <br> functionality.</h3>

        <a class="mt-3 text-cyan-400 inline-flex items-baseline px-2">About the Glimmer Token
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
          </svg>
    </a>



    </div>




    
 <div class="lg:flex-grow md:w-1/2 lg:pl-10 md:pl-16 flex flex-col    ">
      <div class="mt-8 grid lg:grid-cols-2 gap-8  ">
        


        <div class="bg-gray-800"><h2 class="title-font font-medium text-xl text-white mt-5 px-16 py-6 ">Smart Contract Execution</h2> 

          <h3 class="text-white mt-2 px-16 mb-16  ">Glimmer is used to pay for smart <br>contract execution, playing the same <br> role that ETH does on Ethereum.</h3>

</div>
        <div class="bg-gray-800"><h2 class="title-font font-medium text-xl text-white mt-5 px-16 py-6  ">Transaction Fees</h2> 

          <h3 class="text-white mt-2 px-16 mb-16 ">All transaction fees are paid for with <br>Glimmer.</h3></div>

        <div class="bg-gray-800"><h2 class="title-font font-medium text-xl text-white mt-5 px-16 py-6"> Staking</h2> 
  
          <h3 class="text-white mt-2 px-16 mb-16 ">Nominate collators using the Glimmer <br> token and help support the liveness of <br> the network.</h3>
</div>
        <div class="bg-gray-800"> <h2 class="title-font font-medium text- text-white mt-5 px-16 py-6 ">Governance</h2> 
    
          <h3 class="text-white mt-2 px-16 mb-16- ">Participate in on-chain Glimmer- <br>weighted voting and governance.</h3>
</div>

       </div>
    
 </div>

  </div>
</section>



<!--Section 6 Project Roadmap-->


<section class="text-white body-font bg-black">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col ">
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0 px-20">
      <img class="object-cover object-center rounded" alt="hero" src="../assets/Roadmap-100.png">


     
        <h1 class="title-font sm:text-4xl text-3xl  font-medium text-white  px-0 mt-5">Project Roadmap</h1>

</div>








<div class="lg:flex-grow md:w-1/2 lg:pl-10 md:pl-16 flex flex-col    ">

  <h1 class="title-font text-xl  font-medium text-white  px-0 mt-5">Launch Timeline and Progress</h1>


  <div class="flex relative pb-12  mt-12 ">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-400 pointer-events-none">


</div>
</div>






    
    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">



      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">January 2020</h2>
      <p class="leading-relaxed">Project Started</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>



    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">July 2020</h2>
      <p class="leading-relaxed">Awarded a W3F grant for Substrate-based Ethereum compatibility features</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>



    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">September 2020</h2>
      <p class="leading-relaxed">Moonbase Alpha TestNet Launched</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>





    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">October 2020</h2>
      <p class="leading-relaxed">Publish-Subscribe Capabilities Added</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>

    






   
    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">November 2020</h2>
      <p class="leading-relaxed">Transforms Account Structure to Match Ethereum</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>



    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">June 2021</h2>
      <p class="leading-relaxed">Began Moonriver Launch on Kusama</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>

  

    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">August 2021</h2>
      <p class="leading-relaxed">Completed Moonriver Launch on Kusama</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>




    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">December 2021</h2>
      <p class="leading-relaxed">Began Moonbeam Launch on Polkadot</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>




    <div class="flex-shrink-0 w-10 h-10 rounded-full bg-black inline-flex items-center justify-center text-white relative z-10">


      <svg class="h-12 w-12 text-white"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
      </svg>
      
     
    </div>
    <div class="flex-grow pl-4">
      <h2 class="font-medium title-font text-sm text-white mb-1 tracking-wider">January 2022</h2>
      <p class="leading-relaxed">Completed Moonbeam Launch on Polkadot</p>
    </div>
  </div>
  <div class="flex relative pb-12">
    <div class="h-full w-10 absolute inset-0 flex items-center justify-center">
      <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
    </div>

  </div>


</div>
</div>

 </section>



<!--Section 7 Ecosystem-->


 <section class="text-white body-font bg-gray-800">
        <div class="container px-5 py-24 mx-auto  ">

          <div class="text-center mb-20">
            <h1 class="sm:text-5xl font-medium title-font text-white mb-4 "> 
              Join the Moonbeam Ecosystem</h1>
</div>



          <div class="flex flex-wrap -m-4">
            <div class="p-4 lg:w-1/3">
              <div class="h-full bg-gray-700 border-gray-600 bg-opacity-75 px-8 pt-16 pb-24 rounded-lg overflow-hidden text-center relative first-letter:">
               
                <h1 class="title-font sm:text-2xl text-xl font-medium text-white  text-left px-8">Projects</h1>
                <p class="leading-relaxed mb-3 text-left px-8">Teams and developers that want to <br> build on - or integrate with - <br> Moonbeam partnerships, grants, <br> support, and other programs. </p>
                <a class="text-white inline-flex items-center">View Active Projects
                  <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M5 12h14"></path>
                    <path d="M12 5l7 7-7 7"></path>
                  </svg>
                </a>
               
                <div class="text-center mt-2 leading-none flex justify-center absolute bottom-0 left-0 w-full py-4">
                  <span class="text-gray-400 mr-3 inline-flex items-center leading-none text-sm pr-3 py-1 border-r-2 border-gray-700">
                   
                  </span>

                  <span class="text-gray-400 inline-flex items-center leading-none text-sm">
                   
                  </span>
                </div>
              </div>
            </div>
            <div class="p-4 lg:w-1/3">
              <div class="h-full bg-gray-700 border-gray-600 bg-opacity-75 px-8 pt-16 pb-24 rounded-lg overflow-hidden text-center relative">
               
                <h1 class="title-font sm:text-2xl text-xl font-medium text-white mb-3 text-left px-8">Collators</h1>
                <p class="leading-relaxed mb-3 text-left px-8">Earn protocol-level MOVR and GLMR <br> rewards by providing block production <br> and supporting the liveness of the <br> network.</p>
                <a class="text-white inline-flex items-center">BECOME A COLLATOR
                  <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M5 12h14"></path>
                    <path d="M12 5l7 7-7 7"></path>
                  </svg>
                </a>
                <div class="text-center mt-2 leading-none flex justify-center absolute bottom-0 left-0 w-full py-4">
                  <span class="text-gray-400 mr-3 inline-flex items-center leading-none text-sm pr-3 py-1 border-r-2 border-gray-700">
                    
                  </span>
                  <span class="text-gray-400 inline-flex items-center leading-none text-sm">
                    
                  </span>
                </div>
              </div>
            </div>
            <div class="p-4 lg:w-1/3">
              <div class="h-full bg-gray-700 border-gray-600 bg-opacity-75 px-8 pt-16 pb-24 rounded-lg overflow-hidden text-center relative">
              
                <h1 class="title-font sm:text-2xl text-xl font-medium text-white mb-3 text-left px-8">Technology Parterners</h1>
                <p class="leading-relaxed mb-3 text-left px-8">Support,grants, and Partnership <br> programs for providers of developer <br> tooling, infrastructure, <br> implementation, and other necessary <br> ecosystem services.</p>
                <a class="text-white inline-flex items-center">CONTACT US
                  <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M5 12h14"></path>
                    <path d="M12 5l7 7-7 7"></path>
                  </svg>
                </a>
                <div class="text-center mt-2 leading-none flex justify-center absolute bottom-0 left-0 w-full py-4">
                  <span class="text-gray-400 mr-3 inline-flex items-center leading-none text-sm pr-3 py-1 border-r-2 border-gray-800">
                    
                  </span>
                  <span class="text-gray-400 inline-flex items-center leading-none text-sm">
                  
                  </span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>





<!--Section 8 Project Updates-->


<section class="flex flex-col  mx-auto overflow-hidden   bg-gray-900 md:flex-row md:h-72">
        <div class="md:flex md:items-center md:justify-center md:w-1/2 md:bg-gray-900 md:dark:bg-gray-900">
            <div class="px-6 py-6 md:px-8 md:py-0">
                <h2 class="text-4xl font-semibold text-white">Sign Up For <br> Project Updates </h2>
                
                <p class="mt-2 text-lg text-white  ">Keep up with the latest project deployments and <br>network updates!</p>
            </div>
        </div>

       

        <div class="flex items-center justify-items-center ml-0 pl-1  ">
      
              <div class="flex flex-col pb-6 ml-1overflow-hidden border aspect-square-lg dark:border-white lg:flex-row dark:focus-within:border-blue-300 focus-within:ring focus-within:ring-opacity-40 focus-within:border-blue-400 focus-within:ring-blue-300 w-96 h-12 ">
                  
              <input class="px-3 py-5  text-gray-700 placeholder-gray-500 bg-white outline-none dark:bg-gray-900 dark:placeholder-gray-400 focus:placeholder-transparent dark:focus:placeholder-transparent " type="text" name="email" placeholder="email address" aria-label="email address">
              </div>
              </div>
              <div class=" flex items-center justify-items-center ml-10 ">
                <button class="text-white bg-pink-600 border-0  py-2 px-10 hover:bg-pink-700  text-lg w-72 h-12">Send Me Updates</button>
        
       
              </div>

 </section>





<!--Section 9 Footer-->


<section class="text-gray-400 body-font">
      <div class="container px-5 py-24 mx-auto bg-gray-800 ">
        <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto text-center">
          
          <p class="leading-relaxed text-lg ">The Moonbeam protocol is built and powered by</p>
         
           <img class=" mx-auto mt-4 " alt="hero" src="../assets/PureStake-Logo-Final-Inverted_Logo-Horizontal-400px-300x98.png">
           <button class="border border-gray-800 text-gray-200 hover:text-pink-600 rounded px-6 py-6 text-sm ">Privacy Policy</button>
           <button class="border border-gray-800 text-gray-200 hover:text-pink-600 rounded px-6 py-6 text-sm ">  Terms of Use</button>
        </div>

        <div>
          <div class="font-bold mt-12 border-b border-x-gray-700"></div>
        </div>



          <div class="sm:flex justify-around pr-16 pt-8 ">
            <ul class="text-gray-400 sm:self-center text-xl border-t sm:border-none">

              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white  p-4">
                <svg class="h-5 w-5 text-gray-400 hover:text-white"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z" /></svg>             
              </li>


              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg class="h-5 w-5 text-gray-400 hover:text-white"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z" />  <rect x="2" y="9" width="4" height="12" />  <circle cx="4" cy="4" r="2" /></svg>
              </li>

              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg class="h-6 w-6 text-gray-400 hover:text-white "  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z" />  <polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02" /></svg>
              </li>

              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg class="h-6 w-6 text-gray-400 hover:text-white"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22" /></svg>
              </li>

              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg class="h-6 w-6 text-gray-400 hover:text-white"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <path d="M15 10l-4 4l6 6l4 -16l-18 7l4 2l2 6l3 -4" /></svg>
              </li>


              
              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg class="h-6 w-6 text-gray-400 hover:text-white"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <polyline points="3 7 9 4 15 7 21 4 21 17 15 20 9 17 3 20 3 7" />  <line x1="9" y1="4" x2="9" y2="17" />  <line x1="15" y1="7" x2="15" y2="20" /></svg>
              </li>

               
              <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-discord" viewBox="0 0 16 16">
                  <path d="M13.545 2.907a13.227 13.227 0 0 0-3.257-1.011.05.05 0 0 0-.052.025c-.141.25-.297.577-.406.833a12.19 12.19 0 0 0-3.658 0 8.258 8.258 0 0 0-.412-.833.051.051 0 0 0-.052-.025c-1.125.194-2.22.534-3.257 1.011a.041.041 0 0 0-.021.018C.356 6.024-.213 9.047.066 12.032c.001.014.01.028.021.037a13.276 13.276 0 0 0 3.995 2.02.05.05 0 0 0 .056-.019c.308-.42.582-.863.818-1.329a.05.05 0 0 0-.01-.059.051.051 0 0 0-.018-.011 8.875 8.875 0 0 1-1.248-.595.05.05 0 0 1-.02-.066.051.051 0 0 1 .015-.019c.084-.063.168-.129.248-.195a.05.05 0 0 1 .051-.007c2.619 1.196 5.454 1.196 8.041 0a.052.052 0 0 1 .053.007c.08.066.164.132.248.195a.051.051 0 0 1-.004.085 8.254 8.254 0 0 1-1.249.594.05.05 0 0 0-.03.03.052.052 0 0 0 .003.041c.24.465.515.909.817 1.329a.05.05 0 0 0 .056.019 13.235 13.235 0 0 0 4.001-2.02.049.049 0 0 0 .021-.037c.334-3.451-.559-6.449-2.366-9.106a.034.034 0 0 0-.02-.019Zm-8.198 7.307c-.789 0-1.438-.724-1.438-1.612 0-.889.637-1.613 1.438-1.613.807 0 1.45.73 1.438 1.613 0 .888-.637 1.612-1.438 1.612Zm5.316 0c-.788 0-1.438-.724-1.438-1.612 0-.889.637-1.613 1.438-1.613.807 0 1.451.73 1.438 1.613 0 .888-.631 1.612-1.438 1.612Z"/>
                </svg>
    
              </li>


                <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                  <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                  width="24" height="24"
                  viewBox="0 0 50 50"
                  style=" fill:white"><path d="M 29 3 C 28.0625 3 27.164063 3.382813 26.5 4 C 25.835938 4.617188 25.363281 5.433594 25 6.40625 C 24.355469 8.140625 24.085938 10.394531 24.03125 13.03125 C 19.234375 13.179688 14.820313 14.421875 11.28125 16.46875 C 10.214844 15.46875 8.855469 14.96875 7.5 14.96875 C 6.089844 14.96875 4.675781 15.511719 3.59375 16.59375 C 1.425781 18.761719 1.425781 22.238281 3.59375 24.40625 L 3.84375 24.65625 C 3.3125 26.035156 3 27.488281 3 29 C 3 33.527344 5.566406 37.585938 9.5625 40.4375 C 13.558594 43.289063 19.007813 45 25 45 C 30.992188 45 36.441406 43.289063 40.4375 40.4375 C 44.433594 37.585938 47 33.527344 47 29 C 47 27.488281 46.6875 26.035156 46.15625 24.65625 L 46.40625 24.40625 C 48.574219 22.238281 48.574219 18.761719 46.40625 16.59375 C 45.324219 15.511719 43.910156 14.96875 42.5 14.96875 C 41.144531 14.96875 39.785156 15.46875 38.71875 16.46875 C 35.195313 14.433594 30.800781 13.191406 26.03125 13.03125 C 26.09375 10.546875 26.363281 8.46875 26.875 7.09375 C 27.164063 6.316406 27.527344 5.757813 27.875 5.4375 C 28.222656 5.117188 28.539063 5 29 5 C 29.460938 5 29.683594 5.125 30.03125 5.40625 C 30.378906 5.6875 30.785156 6.148438 31.3125 6.6875 C 32.253906 7.652344 33.695313 8.714844 36.09375 8.9375 C 36.539063 11.238281 38.574219 13 41 13 C 43.75 13 46 10.75 46 8 C 46 5.25 43.75 3 41 3 C 38.605469 3 36.574219 4.710938 36.09375 6.96875 C 34.3125 6.796875 33.527344 6.109375 32.75 5.3125 C 32.300781 4.851563 31.886719 4.3125 31.3125 3.84375 C 30.738281 3.375 29.9375 3 29 3 Z M 41 5 C 42.667969 5 44 6.332031 44 8 C 44 9.667969 42.667969 11 41 11 C 39.332031 11 38 9.667969 38 8 C 38 6.332031 39.332031 5 41 5 Z M 25 15 C 30.609375 15 35.675781 16.613281 39.28125 19.1875 C 42.886719 21.761719 45 25.226563 45 29 C 45 32.773438 42.886719 36.238281 39.28125 38.8125 C 35.675781 41.386719 30.609375 43 25 43 C 19.390625 43 14.324219 41.386719 10.71875 38.8125 C 7.113281 36.238281 5 32.773438 5 29 C 5 25.226563 7.113281 21.761719 10.71875 19.1875 C 14.324219 16.613281 19.390625 15 25 15 Z M 7.5 16.9375 C 8.203125 16.9375 8.914063 17.148438 9.53125 17.59375 C 7.527344 19.03125 5.886719 20.769531 4.75 22.71875 C 3.582031 21.296875 3.660156 19.339844 5 18 C 5.714844 17.285156 6.609375 16.9375 7.5 16.9375 Z M 42.5 16.9375 C 43.390625 16.9375 44.285156 17.285156 45 18 C 46.339844 19.339844 46.417969 21.296875 45.25 22.71875 C 44.113281 20.769531 42.472656 19.03125 40.46875 17.59375 C 41.085938 17.148438 41.796875 16.9375 42.5 16.9375 Z M 17 22 C 14.800781 22 13 23.800781 13 26 C 13 28.199219 14.800781 30 17 30 C 19.199219 30 21 28.199219 21 26 C 21 23.800781 19.199219 22 17 22 Z M 33 22 C 30.800781 22 29 23.800781 29 26 C 29 28.199219 30.800781 30 33 30 C 35.199219 30 37 28.199219 37 26 C 37 23.800781 35.199219 22 33 22 Z M 17 24 C 18.117188 24 19 24.882813 19 26 C 19 27.117188 18.117188 28 17 28 C 15.882813 28 15 27.117188 15 26 C 15 24.882813 15.882813 24 17 24 Z M 33 24 C 34.117188 24 35 24.882813 35 26 C 35 27.117188 34.117188 28 33 28 C 31.882813 28 31 27.117188 31 26 C 31 24.882813 31.882813 24 33 24 Z M 34.15625 33.84375 C 34.101563 33.851563 34.050781 33.859375 34 33.875 C 33.683594 33.9375 33.417969 34.144531 33.28125 34.4375 C 33.28125 34.4375 32.757813 35.164063 31.4375 36 C 30.117188 36.835938 28.058594 37.6875 25 37.6875 C 21.941406 37.6875 19.882813 36.835938 18.5625 36 C 17.242188 35.164063 16.71875 34.4375 16.71875 34.4375 C 16.492188 34.082031 16.066406 33.90625 15.65625 34 C 15.332031 34.082031 15.070313 34.316406 14.957031 34.632813 C 14.84375 34.945313 14.894531 35.292969 15.09375 35.5625 C 15.09375 35.5625 15.863281 36.671875 17.46875 37.6875 C 19.074219 38.703125 21.558594 39.6875 25 39.6875 C 28.441406 39.6875 30.925781 38.703125 32.53125 37.6875 C 34.136719 36.671875 34.90625 35.5625 34.90625 35.5625 C 35.207031 35.273438 35.296875 34.824219 35.128906 34.441406 C 34.960938 34.058594 34.574219 33.820313 34.15625 33.84375 Z"></path></svg>
                </li>
  

                <li class="sm:inline-block w-14 h-14 rounded-full border border-gray-400 hover:border-white p-4">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
                    <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
                  </svg>
                </li>




        







            </ul>
          </div>
          <div class="mt-8 w-full mx-auto text-center">
            <p class="leading-relaxed text-xs ">© 2022 PureStake, Inc. All Rights Reserved.</p>
          </div>


        </div>





     </section>







         
</template>

<script setup>
import{ref} from"vue";

const showMobileMenu = ref(true);

</script>
