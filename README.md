Second Exercise (Modules)
=================================================

Please complete the following steps:
 
1. Create a **"sentiment"** module from the sentiment functionality created in the previous exercise, and use it in your TCP server implementation. Do it by:
 * Creating a directory named **"sentiment"**
 * Creating a file named **"index.js"** inside the **"sentiment"** directory
 * Moving the sentiment functionality to the created **"index.js"** and exposing it as a module
 * Using the new **"sentiment"** module from your TCP server implementation
2. Use the **"[require.async](https://github.com/pinf/require.async)"** community module to load the AFINN.json dictionary asynchronously inside your **"sentiment"** module (**HINT: your "sentiment" processing code should be run asynchronously, right after "[require.async](https://github.com/pinf/require.async)" has completed loading the AFINN.json dictionary**)

#####Use the AFINN.json in this repository for the score calculations
#####*You can also use the boilerplate index.js as a starting point for your server code*
