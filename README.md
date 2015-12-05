# ChatApp_Jitesh_Juby_SoftwareDesign
ChatApp-Juby&amp;Jitesh
ReadMe:
Steps to set the application (using Windows machine –install node.js)
1.	Create a folder in desired location say desktop. Give a desired name, we gave work.             NOTE: go to index.js and change the folder name to your folder in the below given screen shot. 

 
2.	Open command prompt/terminal and navigate to your folder ie work. We will navigate using command cd Example: cd Desktop then cd work.
 

NOTE: To create pakage.json file and download modules

Create a package.json file in work folder that will describe the project.                                Command used  in Terminal >npm init
Install Express, path, HTTP and socket.io in your folder (work) .                                                  Command used in Terminal                                                                                                                          >npm install Express                                                                                                                                       >npm install socket.io                                                                                                                                      >npm install http                                                                                                                                     >npm install path
NOTE: Folder named node_modules will be created in your working folder. With the installed libraries
Next we need to save information about the dependencies in package.json hence use the following commands in terminal (Location should be your working folder ie work)                                                                                      >npm install --save Express                                                                                                                           >npm install --save socket.io                                                                                                                     >npm install –save http                                                                                                                           >npm install –save path


3.	To start the server go to terminal same path/location as above (in our case) and execute the following command: >node index.js                                                                   This will show the following output in Terminal:
 
4.	Once you see ‘listening on ***:3000’ go to google chrome and type the following                              url : http://localhost:3000/
5.	This will display home page of Peer Counselling Chat App. Click Next to go to required Chat Application.

