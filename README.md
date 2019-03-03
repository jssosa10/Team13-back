# Team13-back

Para correr el programa primero instale las dependencias necesarias con:

    npm install
            
Luego, corralo con start

    npm start
  
 ## Clase Chat

 Get de todos los chats o por ID.
 
    http://localhost:3000/chat
    
    http://localhost:3000/chat?id=614532168092341000000
    
 Post de un chat
 
      {	
        "messages": [
            {
                "text": "TEXTO PRUEBA TEXTO PRUEBA PRUEBA PRUEBA\r\n",
                "timeStamp": "Tue Feb 17 2015 19:16:26 GMT-0500 (Colombia Standard Time)}",
                "userID": "5c7bf45a50dabdff479f59f8"
            },
            {
                "_id": "5c7bebc2421fe5dd93f96829",
                "text": "Veniam minim consequat deserunt culpa est et reprehenderit. Adipisicing ea dolor dolore laboris pariatur deserunt ad non. Adipisicing minim ea et laborum sit do eiusmod veniam. Occaecat ex non dolor laborum anim ad aute non minim. Ut culpa dolor quis labore veniam elit. Eiusmod ad ullamco velit laboris elit velit laborum mollit officia dolor ipsum.\r\n",
                "timeStamp": "Thu May 15 1997 21:24:24 GMT-0500 (Colombia Standard Time)}",
                "userID": "5c7bf45aeb01e62096576f3c"
            }
        ]
    }

 Delete de un chat por ID
 
    http://localhost:3000/chat?id=614532168092341000000
 
 Update/PUT de un chat por ID
 
    http://localhost:3000/chat?id=707620319244405600000
    
      {
      "messages": [{
                    "text": "TEXTO PRUEBA TEXTO PRUEBA PRUEBA PRUEBA\r\n",
                    "timeStamp": "Tue Feb 17 2015 19:16:26 GMT-0500 (Colombia Standard Time)}",
                    "userID": "5c7bf45a50dabdff479f59f8"
                }]
        }
 

 ## Clase Mensaje de Chat
 
 Get de todos los chats o por ID.
 
    http://localhost:3000/chatmsg
    
    http://localhost:3000/chatmsg?id=5c7bed121829835899501913
    
 Post de un mensaje de chat
 
    {	
       "text": "MAS NUEVO MAS NUEVO ut eiusmod. Adipisicing aliquip aute pariatur aliquip excepteur eiusmod ad commodo.\r\n",
        "timeStamp": "Wed Dec 06 1978 08:26:10 GMT-0500 (Colombia Standard Time)}",
        "userID": "5c7bf45a50dabdff479f59f8"
    }

 Delete de un mensaje de chat por ID
 
    http://localhost:3000/chatmsg?id=5c7bed124a4d3a10d83c7325
 
 Update/PUT de un mensaje de chat por ID
 
    http://localhost:3000/chatmsg?id=5c7bed121829835899501913
    
    {	
       "text": "ALGO MAS NUEVO NUEVO ut eiusmod. Adipisicing aliquip aute pariatur aliquip excepteur eiusmod ad commodo.\r\n",
        "timeStamp": "Wed Dec 06 1978 08:26:10 GMT-0500 (Colombia Standard Time)}"
    }
 
  ## Clase Comentario
 
 Get de todos los comentarios o por ID.
 
    http://localhost:3000/comment
    
    http://localhost:3000/comment?id=5c7be48d8f4a30514ff3fab3
    
 Post de un comentario
 
    {	
       "text": "MAS NUEVO MAS NUEVO ut eiusmod. Adipisicing aliquip aute pariatur aliquip excepteur eiusmod ad commodo.\r\n",
        "timeStamp": "Wed Dec 06 1978 08:26:10 GMT-0500 (Colombia Standard Time)}",
        "userID": "5c7bf45a50dabdff479f59f8"
    }

 Delete de un comentario
 
    http://localhost:3000/comment?id=417077870346140700000
 
 Update/PUT de un comentario de chat por ID
 
    http://localhost:3000/comment?id=417077870346140700000
    
    {	
       "text": "BBBBBBBBBB excepteur eiusmod ad commodo.\r\n",
        "timeStamp": "Wed Dec 06 1978 08:26:10 GMT-0500 (Colombia Standard Time)}",
        "userID": "5c7bf45a50dabdff479f59f8"
    }
 
 
