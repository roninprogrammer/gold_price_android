# gold_price_android
Gold Price Android

1. Create a sign up screen that can call the registration endpoint, and get them to input per tinent data using a format. 
     a .https://staging.hellogold.com/api/v3/users/register.json 
     
      The endpoint takes the following parameters via <b>POST</b>
      ````
         1. email (Take this input from the user, must be valid email format)
         2. uuid (This is a randomly generated UUID)
         3. data (This is a random string that is 256 bits long)
         4. tnc (This is a boolean string, either send in either “true” or “false”,take this from the user in a checkbox)
      ``````    
      b. Once the registration is complete, take the user to a dashboard/landingpage/landing view where they can see the price of gold today, so:-
               
2. Create a dashboard/landing page/landing view where you can see a listing of the price,this endpoint returns one price per call, so you need to make multiple calls to make ahistorical list of prices.
    a. https://staging.hellogold.com/api/v2/spot_price.json 
3. From this, populate a view that consists of a list with the price. The view/storyboard/whatever should have the following properties/behavior
              
               a. The email of the user is displayed
               b. Can be refreshed via pulling down on the list/view 
               c. Is refreshed whenever the view is displayed, for example after the user closes the app and reopens the app
               d. Is refreshed via a button 
               e. The prices should be displayed in a historical manner, so you can see the price changes across time.
               f.Clean and easily readable code. 
               g. Sufficient test coverage. 
