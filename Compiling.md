# Compiling #
**What you'll need:**
  * Java IDE (in this case, I'll be using Eclipse Juno)
  * The tars in the Downloads Section
  * A copy of the lol-jclient source code. (made with `git clone https://code.google.com/p/lol-jclient/`)
  * Java JDK 7


## Step 1: Add project to Eclipse ##
  * Select File > Import...
  * Select General > Existing Projects into Workspace
  * Select wherever you downloaded the sources

## Step 2: Run ##
  * Select Run > Debug
  * If asked "Selected a way to debug lol-jclient", select Java Application
  * If asked "Select Java Application", select "StartupClass - com.kolakcc.loljclient".
  * Change LoL versions:
    * Open loljclient/src > com.kolakcc.loljclient.util > Configuration.java
    * Change PVPVersion to the number in the top left of the LoL PVP.net client (title screen)
  * It should start up. If not, please message me.

## Step 3: Running without Eclipse ##
  * Select File > Export
  * Select Java > Runnable JAR file
  * Launch Configuration: StartupClass - lol-jclient
  * Put it somewhere.
  * Library handling: Copy required libraries into a sub-folder next to the generated JAR
  * Finish > OK
  * Copy the files in loljclient/lib/sqlite4java to the 