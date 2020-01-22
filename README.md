<h3>Installation Steps For Mac</h3>

<h4>Steps 1: Install Java Development Kit (JDK)</h4>
<pre
Download JDK from the following link
<a href="https://www.oracle.com/technetwork/java/javase/downloads/index.html" target="_blank">https://www.oracle.com/technetwork/java/javase/downloads/index.html</a>

Install the JDK
</pre>

<h4>Steps 2: Setup Java Environment Variable Path</h4>
Open terminal and type the following command to open the .bash_profile file
<pre>nano ~/.bash_profile</pre>
Type the following
<pre>export JAVA_HOME=$(/usr/libexec/java_home)</pre>
Press Ctrl+X to exit the bash profile<br>

Press Y to save the changes and press Enter<br>

<h4>Step 3 : Install Android Studio</h4>
Download the Android studio from the following link<br>
<pre>
<a href="https://developer.android.com/studio/index.html" target="_blank">https://developer.android.com/studio/index.html</a>
</pre>
Install Android studio and move to the Applications.<br>
<br>
Open Android studio, click on “Configure” and Select “SDK Manager” <br>
<img src="https://github.com/codecunning/mobile_automation_configuration_for_mac/blob/master/SDK%20Manager.png" width="750" height="450">
Select “SDK Tools” tab and make sure the highlighted modules are checked and installed.
<img src="https://github.com/codecunning/mobile_automation_configuration_for_mac/blob/master/SDK%20tools.png" width="750" height="450">

<h4>Step 4 : Setup Android Environment Variables</h4>
Open terminal and type the following command to open the .bash_profile file
<pre>nano ~/.bash_profile</pre>
Type the following in the next line
<pre>export ANDROID_HOME=/Users/$USER/Library/Android/sdk
export PATH=${PATH}:$ANDROID_HOME/platform-tools:$ANDROID_HOME/emulator:$ANDROID_HOME/tools/bin:ANDROID_HOME/tools</pre>
Press Ctrl+X to exit the bash profile
<br>
Press Y to save the changes and press Enter

<h4>Step 5 : Download and install Appium Desktop Client</h4>
Download the stable appium desktop for mac (.dmg file) from
<pre><a href="https://github.com/appium/appium-desktop/releases">https://github.com/appium/appium-desktop/releases</a></pre>
<br>
Install appium desktop client and move the appium to the applications folder

<h4>Step 6 : Download and Install XCode</h4>

<ol type="i">
  <li>
    Download Xcode from 
    <pre><a href="https://developer.apple.com/download/">https://developer.apple.com/download/</a></pre>
  </li>
  <li>Provide the apple id and password</li>
  <li>Download the stable version of xcode and install it and move it to Applications</li>
  <li>
  Download XCode Command Line Tools from
  <pre><a href="https://developer.apple.com/download/more/">https://developer.apple.com/download/more/</a></pre>
  </li>
  <li>The command line tools should be the same version of xcode or the lower version of xcode If xcode version is 9.3.3 and   command line tools can be of 9.3.2 6. Install XCode Command Line Tools</li>
</ol>

<h4>Step 7 : Install Node JS</h4>
<ol type="i">
  <li>Prerequisite<br>
            a. Before install Node, you should need to install Homebrew
               Homebrew is a package manager for the Mac — it makes installing most open source software (like Node) as simple
            b. Open the Terminal app and type
  <pre>ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2>/dev/null</pre>
  </li>
  <li>Open the Terminal app and type
    <pre>brew install node</pre>
  </li>
  <li>To make sure you have Node and NPM installed, run two simple commands to see what version of each is installed
    <pre>node -v</pre>
  </li>








