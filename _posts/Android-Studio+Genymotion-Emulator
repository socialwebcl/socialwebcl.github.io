Android Studio + Genymotion Emulator

The Android emulator is dog slow. The x86 intel emulators only work with certain versions of OSX, otherwise they crash miserably.

Genymotion is apparently pretty good, so I’m giving that a shot.

Here’s how to do it.

Download and Install VirtualBox

Download VirtualBox + follow instructions to install.

Signup with Genymotion + Download installer

Go to genymotion.com and signup

Click the “Get Genymotion” button and download the appropriate version for your OS.

Run the Genymotion application

It will install Genymotion and Genmotion shell — run the Genymotion application (not the shell).

When you run it, you will see:

Screenshot

Click add new virtual device. It will ask you to login, then show you a list:

Screenshot

Pick the virtual device you want and it will download it.

Try starting a virtual device

Here’s what happened on my system:

Hit Play to run virtual device
It asked me to configure the Android SDK location, I said “No”
Then it gave me an error that VirtualBox was not installed
I started VirtualBox manually
I retried running the virtual device, this time it worked and I saw
Screenshot

Configure Android Studio plugin

Go to Preferences / Plugins and click “Browse Repositories”, then search for Genymotion. Right click and choose “Download and Install”.

Screenshot

Restart Android Studio and you should see a new icon in your IDE.

Screenshot

Click the icon and it will bring up Preferences, and choose the path to the Genymotion application.

Screenshot

Now if you click the Genymotion icon again, you will see the list of devices available:

Screenshot

Start an emulator

Click the Genymotion icon within Android studio, select a virtual device, and hit start.

It will ask you to choose the location of the SDK:

Screenshot

On Mac OSX, I was not able to brows to the path since the application was greyed out in the chooser dialog, so I went onto the shell and found it (/Applications/Android Studio.app/sdk) and just copied and pasted it:

Screenshot

Select a virtual device, and hit start (again). It should come up now.

Deploy an application/test to that emulator

In Android Studio, hit the “Play” or “Debug” button, and you should see the dialog that asks you to choose an emulator:

Screenshot

and one of the emulators will be the Genymotion emulator. After you choose that emulator and hit “OK”, it will run your application in the Genymotion emulator (this is showing the Grocery Sync demo app for Couchbase Lite):

Screenshot

