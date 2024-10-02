# Transfer-Playlist | Project Spopple

## Creating an application that will transfer any songs you will have on spotify to apple music or any platform of my choosing
 ### The Challenges however...
    
   * I don't know APIs worth shiiieeet
   * I can't really understand what the API code is even saying sometimes
   * I am not sure how to apply this in my prefferred language of Java/kotlin
   * this going to be a non-gui application so i have no sense of direction.
   * so this will be fun.

#### This is the objective / plan
    _____ Objective: ________________________________________________________________________________________________________________________
    |                                                                                                                                       |
    |  while I am sure there is an existing application for this very problem, I am too lazy to find and verify.                            |
    |  I also don't understand shit when i read the available open source code.                                                             |
    |  Why not build one from scratch and fix this very problem in terms of the technical aspect?                                           |
    |  I dislike that there is not a easy way without potential paywalls to transfer my playlist                                            |
    |  from one application, I understand companies want to retain their customer,                                                          |
    |  but I am not a child and should not be babied and kept in one ecosystem.                                                             |
    |                                                                                                                                       |
    |     I need an easy solution to transfer or make a copy of my playlist in my current platform to another platform if i so choose to    |
    |     I want to build an application that will allow me to do the following:                                                            |
    |           1. paste my api token to access my content                                                                                  |
    |           2. ability to display the available playlist in alphabetical list (not show any deleted playlist)                           |
    |           3. ability to select the playlist by entering the phrase: select [playlistname]                                             |
    |           4. With the selected playlist, choose the following available platform (for now kiss, we're using apple music only)         |
    |               a. your api token key should already be pasted in the codebase, if it doesn't it will not continue nor work             |
    |           5. output informing me if the playlist copy was successful or not successful                                                |
    |               a. If successful and made a full copy, end program                                                                      |
    |               b. if unsuccessful, go back to step 4                                                                                   |
    _________________________________________________________________________________________________________________________________________

    _____ preplanned function _______________________       _____ Current Variable Names _____
    |                                               |       |                                |
    |       information func  (the main i think)    |       |   string SpotifyAPI            |
    |       displayAvailablePlaylist func           |       |   string AppleAPI              |
    |       choosePlatform func                     |       |   ? spotifyPlaylist            |
    |           apple()                             |       |   ? applePlaylist              |
    |               [OPTIONAL]                      |       |   ? createPlaylist             |
    |                   tidal()                     |       |   ? trackURI                   |
    |                   amazon()                    |       __________________________________
    |                   youtube()                   |
    |       successOutput func                      |
    |           if(success)                         |
    |               stop program                    |
    |           else                                |
    |               choosePlatform()                |
    _________________________________________________
