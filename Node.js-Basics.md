# 1. What is Node.js ? Is it a Framework or any Language ?
 Node.js is neither a framework ,nor any language . It is a JavaScript runtime environment that allows JS code to executed on the SERVER side. 
 Browsers executes JS code on the CLIENT Side ( eg : v8 engiene of Chrome ) and Node.js executes JS code on the server side . Node.js is basically built on the v8 engiene of Chrome . 
 
 <img width="1000" height="1000" alt="Screenshot 2026-02-08 101413" src="https://github.com/user-attachments/assets/5bc70dd5-dee0-44b6-a741-700f83125fa5" />

# 2. What is the difference between a Runtime Env and Framerwork ? 
  Runtime Environments basically provides the necessary infrastruture for code execution ( by converting -> High Level Language to Machine Level Language ) and also provide some basic facilities 
  like memory management , I/O operations . 
  On the other hand , a Framework is always built on the top of any language , it provides the necessary facilities for development puroposes by providing a lot of tools, in built libraires etc.
  E.g : Node.js is a runtime environment and Express.js is a framework . Node.js provides a platform for javascript code execution whereas Express.js is a framework which is built on the top of Javascript language
  and uses node.js as a runtime environment .

# 3. What is the difference between Client Side and Server Side ?
  Client Side is mainly the browser . It's runtime environment is mainly the Browser whereas the runtime environment of Server side is the Server . Client side handles all the UI and rendering logic wherease the 
  server side handles all the buisness logic like Database , authentication & authorization . Client side does not contain any REQUEST / RESPONSE object but the server side contains REQUEST / RESPONSE object .
  Client side contains WINDOW / DOCUMENT MANIPULATION objects but the server side does not contain them . 
  
  <img width="1000" height="1000" alt="Screenshot 2026-02-08 101940" src="https://github.com/user-attachments/assets/58fe9e8f-fd1e-474e-8cae-65f731674572" />

# 4. How does WEB WORKS behind the Scences ? 
  In simple words , If we say how web works behind the scenes .. the ans should be via Request <-> Response Model or the Client-Server Architechture where the Client sends some request from the Web to the Server 
  where it is hosted . 
  
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/a055833d-ddfb-4ce3-8096-853917664088" />
  
  Every URL ( has its domain name : eg : www.google.com ) , where the URL is sent to the DNS Server at first which contains the IP ADDRESS of the URL . After the IP ADDRESS , is fetched successfully from the 
  DNS Server => a TCP /IP Connection is setup between the CLIENT and the SERVER . This TCP connection decides how the data would be shared over Internet . After that REQUEST is sent from the CLIENT side to 
  SERVER side through HTTP / HTTPS protocols .
  
  <img width="500" height="500" alt="Screenshot 2026-02-08 113210" src="https://github.com/user-attachments/assets/f6ab86ec-7a09-4433-bca7-de61588877ad" />

  How the TCP Protocol transfers the Request and Response data over the internet = > TCP breaks the entire request / response data into 1000's small chunks called packets and these small packets travel over the 
  internet through different routes and all these packets are assembled together before reaching the destination by the TCP .
  
  <img width="1920" height="1080" alt="Screenshot 2026-02-08 115153" src="https://github.com/user-attachments/assets/52b3268d-6bf0-4e95-aae3-052b63806321" />


 # 5. How does Client side and Server side rendering differs ? What is Static vs Dynamic vs API Rendered Websites ? 

  Client side rendering occurs in case of API rendered Websites , where the browser renders the pages of the website based on the response from the SERVER ( json response from API ) 
  whereas in case of the server side rendering , the rendering is also done from the server side based on the data logic and the Rendering Template . 

  Server side Rendering : 
  
  <img width="500" height="500" alt="Screenshot 2026-02-15 114510" src="https://github.com/user-attachments/assets/882cdd88-665e-4fa8-92bc-12b145d65fcf" />

  Client Side Rendering : 

  <img width="500" height="500" alt="Screenshot 2026-02-15 114604" src="https://github.com/user-attachments/assets/55e4ba48-7cd5-41d7-ab9d-f40303ef893a" />

  Difference between Static vs Dynamic vs API rendered : 

  <img width="500" height="500" alt="Screenshot 2026-02-15 114648" src="https://github.com/user-attachments/assets/4ccc0de4-7514-4d3e-ae0e-2bb992570ce9" />



