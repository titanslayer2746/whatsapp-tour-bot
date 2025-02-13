# Project Structure
```
whatsapp-tour-bot/
│── 📁 src/                 
│   ├── 📁 config/          
│   │   ├── db.js           
│   │   ├── meta.js          
│   │   ├── twilio.js       
│   │   ├── stripe.js     
│   │  
│   ├── 📁 routes/           
│   │   ├── whatsapp.js      
│   │   ├── payment.js      
│   │  
│   ├── 📁 controllers/        
│   │   ├── whatsappController.js
│   │   ├── aiController.js        
│   │   ├── bookingController.js   
│   │  
│   ├── 📁 models/          
│   │   ├── enquiryModel.js  
│   │   ├── bookingModel.js  
│   │  
│   ├── 📁 utils/            
│   │   ├── generateTour.js  
│   │   ├── sendMessage.js   
│   │  
│   ├── app.js               
│   ├── webhook.js         
│  
│── 📁 tests/                 
│── .env                     
│── package.json             
│── README.md               
```