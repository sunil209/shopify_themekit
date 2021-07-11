Setup Shopify Theme Development with Local repo via Themekit 


Step 1:- Install Themekit 

For Mac : 

brew tap shopify/shopify
brew install themekit


For Windows:
choco install themekit



Step 2:- Get Store access, by installing the "Theme Kit Access app" by Shopify
         App URL - https://apps.shopify.com/theme-kit-access?shpxid=9126df8f-C9DB-4945-F790-85DC9682E9D3


After installing you will get the password i.e key shptka_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx


Step 3: - Go to your local system folder location and run below command 
          theme get --list --password=[your-password] --store="[your-store.myshopify.com]"
          
          
          Note - Replace the password and store URL

Eg: -
theme get --list --password=shptka_xxxxxxxxxxxxxxxxxxxxxxxxxxxxx --store="xxxxxxx.myshopify.com"


Step 4 : - Run theme watch 
           To sync your local development code via shopify store 

