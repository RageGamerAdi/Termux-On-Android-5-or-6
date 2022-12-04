# Run-Termux-On-Old-Android-Devices

<H2>ABOUT:-</H2>
<H4><P>If You are using lower version of Android, Like Android 5 or 6. In this page you will get your solution.</P></H4>

<H2>Download Termux:-</H2>
<P><H4>Download Termux From Given Link Below.</H4>
<pre>https://archive.org/download/termux-repositories-legacy/termux-v0.79-offline-bootstraps.apk</pre>
<H4>After downloading Install it.</H4></P>

<H2>Setup Termux:-</H2>
<P><H4>After installation Paste the following command in Termux.</H4>
<H6>This is one Line Command.</H6>
<pre>termux-setup-storage && cd ../usr/etc/apt/sources.list.d && rm -rf * && cd ~ && cd ../usr/etc/apt/ && rm -f sources.list && echo "deb http://packages.termux.dev/apt/termux-main-21 stable main" > sources.list && cd ~</pre></P>

<H5>Done, After that you can use all termux Commands in your Lower Android Version</H5>
<center><H1>~~~Thanks~~~</H1></center>
