# React-nodejs-deploy-on-GoogleCloud


exports.helloWorld = functions.https.onRequest((req, res) => {
 
    // // res.set("Access-Control-Allow-Origin", "*");
    // // res.set("Access-Control-Allow-Methods", "GET");
    // // res.set("Access-Control-Allow-Headers", "Content-Type");
    // // res.set("Access-Control-Max-Age", "3600");
    res.header("Access-Control-Allow-Origin", "*"); // update to match the domain you will make the request from


    res.header("Access-Control-Allow-Headers", "Origin, X-Requested-With, Content-Type, Accept");



    
        res.send("Hello from Firebase!");
      
   
  
  
});
