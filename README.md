# Android-Messages-Wrapper
This is a wrapper for Android Messages on the web written in C++. This opens a Google Chrome window in the app or headless mode going to https://messages.android.com which will then prompt the user from there to link up their phone. This is a super simplified way to launch Android Messages. This is nothing more than an app that opens a web browser. Please acknowledge, that I acknowledge, that this app just opens a web browser for Android Messages and I am not affiliated with Google.

This is just a C++ wrapper and works in a Unix environment. It was created and tested on Arch linux.
<br /><hr />
<h2>Required:</h2>
<ul>
  <li>Google Chrome Stable</li>
  <li>Internet Connection</li>
</ul>
<br />
<h2>Instructions:</h2>
<ol>
  <li>Install <code>Google Chrome Stable</code> if you have not already!</li>
  <li>Download files: messages, messages.png, messages.desktop, (optional - advanced)messages.cpp</li>
  <li>Open Terminal, <code>CD</code> into directory with downloaded files</li>
  <li>Run <code>chmod +x messages</code></li>
  <li>Run <code>sudo mv messages /usr/bin/</code></li>
  <li>Run <code>sudo mv messages.png /usr/share/icons/</code></li>
  <li>Run <code>sudo mv messages.desktop /usr/share/applications</code></li>
</ol>

<h4>Done, look for smiley message icon in applications menu, or run <code>messages</code> in the terminal to launch application.</h4>
