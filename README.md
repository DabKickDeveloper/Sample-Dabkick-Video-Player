# Sample-Dabkick-Video-Player
The main purpose of this sample application is to familiarize the users with the key functionalities of the video player.

# Getting the code

The source code for the sample app can be found in our [GitHub project](https://github.com/DabKickDeveloper/Sample-Dabkick-Video-Player.git). If you haven’t already done so, clone the project into a local directory:

    git clone https://github.com/DabKickDeveloper/Sample-Dabkick-Video-Player.git

Next, open the project in Android Studio. You should see the following in the Android Project view.
                                        
![Figure1](https://user-images.githubusercontent.com/13344744/44399170-245a2400-a564-11e8-82dd-1963403fa98c.png)
                                       Figure 1 in Android Studio
                                        
                                        

# Compiling and running 

To compile and run the sample app, select and run the app configuration in Android Studio. The sample app will install and run on a connected Android device. We recommend using a physical device if possible and 2 devices in order to fully test the functionalities of the dabkick player. Ensure that your device is with an API level of atleast 14.

Once run successfully, you should be able to see the home page(MainActivity). The sample app homepage presents of a list of videos. Selecting a video will open a second activity (PlayerActivity) for playback as shown in the below image. 

![4866701222374988684](https://user-images.githubusercontent.com/13344744/44450989-0944ee00-a610-11e8-99c4-e3f91f07c66c.jpg)

                                      Figure 3 in Device 1 after selecting a video to play
                                      
                                      
                                      
Clicking on the play button in the video controls should start playing the video, you can invite a friend/another user to 'Watch Together' by tapping on the watch together button provided on the right hand corner of the dabkick player. Upon tapping the button, a custom edit text appears which hints you to enter your name and proceed to tapping on the "Share an invite" option
 
 ![3155727840643022964](https://user-images.githubusercontent.com/13344744/44451017-1f52ae80-a610-11e8-94f2-2e2299bf28b2.jpg)
                                   Figure 4 in Device 1. Tap on the Watch Together button
                                    
  
  
  
![Figure5](https://user-images.githubusercontent.com/13344744/44400997-caa92800-a56a-11e8-89f8-138c241e637c.jpg)
                                    Figure 5 in Device 1. Enter user name and tap on Share an invite.
                                    
                                    
 Upon the above step you should be able to see multiple options for sharing such as hangouts, email etc. Select any of the available options and send it to the desired friend. 
 
 
 ![hangouts](https://user-images.githubusercontent.com/13344744/44451096-53c66a80-a610-11e8-95d2-4d6f89aea5ef.jpg)
                                   Figure 6 in Device 1. Select any of the available options.
 
 Your friend will recieve the url on the other phone and upon clicking on the url the same video will start playing in both the devices in sync.
 
 You may even tap on the chat icon in order to chat with your friend as the video plays along on both ends.
 
 ![chat](https://user-images.githubusercontent.com/13344744/44451104-5d4fd280-a610-11e8-8605-a6e7920bd404.jpg)
                                   Figure 7. Tap on chat icon to chat while playing the video.
                                   
                                   
  You may either click on the back button of your android device or the "X" mark available on the left hand side of the device to exit the video player.
  
 # Supported Device
 
 Min Api level - 14
 
 Target sdk version - 27
 
 Exo player version - 2.8.0
 
 # Integration steps
 
 You can integrate our Dabkick video player into your own app. To do this follow the [integration documentation](https://www.dabkick.com/video_player/Firework/)
 

                                    
              
                                    
  
 


