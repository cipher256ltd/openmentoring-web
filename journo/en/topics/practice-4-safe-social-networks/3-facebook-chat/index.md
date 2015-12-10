# How to chat securely?
<p>Here you can learn how to encrypt your Facebook voice calls and instant messages. By doing so, you can enhance the privacy and security of your communications. The good news is that this is quite easy to do! Continue reading to learn more.  </p>

***<p>Arun and Priya are human rights defenders in south Asia and communicate via Facevook. However, law enforcement agencies in their country are able to intercept their Facebook instant messages and calls because they are unencrypted. As a result, the local police is able to know of their activities in advance and to block them in various occassions.</p>

***<p>When you communicate over Facebook without the use of encryption, the company and all other third parties it potentially shares/discloses your data to (ranging from other advertising companies to law enforcement agencies) can have access to the content of your instant messages (IM) and voice calls (VoIP). Not only can this potentially expose your data to breach, but also that of your contacts. </p>
<p>To enhance the privacy and security of your communications, you can install Jitsi: a client which supports the Off-the-Record (OTR) protocol for IM encryption and ZRTP for VoIP encryption. This not only makes the content of your communications inaccessible to various third parties, such as governments and corporations, but it also makes it inaccessible to the very companies that provide you the service (such as Facebook, if you are using Facebook Chat).</p>

***<p>To encrypt the content of your Facebook instant messages and voice calls, you first need to install Jitsi: a client which supports both Facebook and the Off-the-Record (OTR) protocol for encryption. This section shows you how to do the following: </p>
<p>(1) install Jitsi<br>(2) add your Facebook account on Jitsi
(3) encrypt your Facebook instant messages
(4) encrypt your Facebook voice calls</p>
<p><strong>How to install Jitsi </strong></p>
<p>You can install Jitsi through the following steps:</p>
<p><strong>Step 1</strong>: Download Jitsi through its <a href="https://jitsi.org/Main/Download">website</a>. </p>
<p><strong>Step 2</strong>: Double click on the downloaded Jitsi file; the Open File - Security Warning dialogue box might appear. If it does, click on <em>&quot;Run&quot;</em> to activate the Windows Installer screen, followed by the <em>&quot;Welcome to the Jitsi Setup Wizard&quot;</em> window.</p>
<p><strong>Step 3</strong>: Click on <strong>&quot;Next&quot;</strong> to activate the &quot;End User License Agreement&quot; window; <strong>check</strong> the &quot;I accept the terms in the License Agreement&quot; option to enable the <em>Next</em> button, and then click on <strong>&quot;Next&quot;</strong> to activate the &quot;Destination Folder&quot; window.</p>
<p><strong>Step 4</strong>: Click on <strong>&quot;Next&quot;</strong> to activate the &quot;Additional Tasks&quot; window and accept the default settings as presented.</p>
<p><strong>Note:</strong> Enabling the Auto-start when computer restarts or reboots option may slow down the overall function of your computer, especially if you already have multiple applications configured to run when your computer starts up.</p>
<p><strong>Step 5</strong>: Click on <strong>&quot;Next&quot;</strong> to activate the &quot;Ready to Install Jitsi&quot; window, and then click on <strong>&quot;Install&quot;</strong> to activate the &quot;Installing Jitsi&quot; window displaying the installation progress bar.</p>
<p><strong>Step 6</strong>: Click on <strong>&quot;Finish&quot;</strong> to complete the installation process and automatically launch the &quot;Jitsi Sign in&quot; window as follows:</p>
<p><img src="{{site.baseurl}}/https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-07.png" alt=""></p>
<p><strong>Note:</strong> In some instances, installing and launching Jitsi for the first time triggers a Windows Security Alert prompt screen. This alert is normal behaviour for the MS Windows operating system, it is ok to continue with using Jitsi. Even if you do not click on any of the buttons, and simply close the prompt window, Jitsi is still able to communicate through Facebook Chat. </p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-08.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-08.png</a></p>
<p><strong>Step 7</strong>: Select both Private and Public networks check-boxes, and then click Allow access to see the Jitsi Sign in window or main user interface window.</p>
<p><strong>How to add a Facebook account on Jitsi</strong>
Facebook has two settings that you might need to change before Jitsi can connect to your Facebook Chat.</p>
<p><strong>Facebook Username</strong></p>
<p>Facebook requires a username for Jitsi to connect to Facebook chat. Many Facebook users already have a username. To check your username, log in to your Facebook account: your username is what appears in the location bar of your browser after <a href="https://www.facebook.com/">https://www.facebook.com/</a> when you view your Timeline or Page. Your username is also included in your Facebook email address (e.g. username@facebook.com). </p>
<p>You can get a new Facebook username by going to your Account Settings &gt; General section or by visiting <a href="https://www.facebook.com/username">https://www.facebook.com/username</a>. To set a new username Facebook might want to verify your account, which might require sending an SMS to a mobile phone number which you will need to provide to Facebook in the verification process. For more details see Facebook’s explanation of usernames.</p>
<p><strong>App Settings</strong></p>
<p>Facebook’s “application platform” needs to be turned on before Jitsi can connect to Facebook Chat. Visit your Facebook Account Settings &gt; Apps section and check that the setting for “Apps you use” is turned “On”. </p>
<p><strong>Note:</strong> Turning Facebook’s &quot;application platform&quot; on opens up much of your Facebook data to third-party application developers. This data is available not only to the Facebook applications that you use, but also to the Facebook applications used by any of your friends. After turning on Facebook’s &quot;application platform&quot;, be sure to check the settings under &quot;Apps others use&quot;. This setting allows you to hide some personal information from applications used by your friends. Unfortunately, Facebook does not offer settings to hide all personal information. Certain categories of information (like your friend list, gender, or info you have made public) are visible as long as Facebook’s &quot;application platform&quot; is turned &quot;on&quot;. It is up to you to determine whether this is an acceptable trade-off.</p>
<p>Now you are prepared to add your Facebook account on Jitsi. To do this follow the steps below:</p>
<p><strong>Step 1:</strong> Select <strong>File &gt; Add New Account...</strong> in the main menu bar of Jitsi.</p>
<p><strong>Step 2:</strong> In the &quot;Add New Account&quot; dialogue, <em>Network</em> menu choose Facebook, enter your username and password and Click <strong>&quot;Add&quot;</strong>.</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-16.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-16.png</a></p>
<p><strong>How to encrypt your Facebook instant messages</strong></p>
<p>OTR is supported by Jitsi and can be used to encrypt your instant messages. You can enable the encryption of your instant messages through the following steps:</p>
<p><strong>Step 1:</strong> Select <strong>Tools &gt; Options</strong> from the Jitsi menu and subsequently select the <strong>Security</strong> tab and its <strong>Chat</strong> sub-tab. You will then see a window similar to one shown in the image below:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-35.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-35.png</a> </p>
<p><strong>Step 2:</strong> Click on the <strong>&quot;Generate&quot;</strong> button. As a result you will see the fingerprint of the key that has been generated:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-36.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-36.png</a> </p>
<p>One key is generated for each account. You only need to do this again if you add a new account or install Jitsi on another device and do not move the existing keys to it.</p>
<p>You are now ready to communicate:</p>
<p><strong>Step 3:</strong> Select a contact from the Jitsi main window and click on the <em>send message icon</em> (first from the left under the contact&#39;s name) to open a text chat window:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-37.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-37.png</a></p>
<p>Note the Encrypt chat with OTR icon, the open padlock on the right-top side of the window. This inconspicuous symbol informs you whether the chat is encrypted or not. Now the lock is open (there is a tiny space between handle and the body of the lock!).</p>
<p><strong>Step 4:</strong> Click on the Encrypt chat with OTR icon. Note the changes in the window:
<a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-38.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-38.png</a></p>
<p>Observe that the padlock is now locked. This means that whatever messages you and your contact send to each other are encrypted. Note the message that this is an unverified private conversation and that you should authenticate your contact.</p>
<p><strong>Step 5:</strong> click on the link authenticate sally.the.doer@jit.si to open the Authenticate Buddy window:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-39.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-39.png</a></p>
<p>Note the message that encourages you to compare the fingerprints of your keys with your contact over another channel (not this text chat). In doing this, you can be more certain that you are communicating with your contact and not somebody else. A good choice for key comparisons is to do it face to face, or via video or voice communication as these provide easier means to authenticate the identity of the other person. After you compare fingerprints, select the option I have verified the fingerprint from the pull-down menu and click on Authenticate Buddy:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-40.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-40.png</a> </p>
<p>Closing the Authenticate Buddy window returns you to the chat window:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-41.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-41.png</a> </p>
<p>Note that padlock no longer includes the orange triangle with the white exclamation mark. This means that you have authenticated your contact. The authentication should be done only once per contact. If the triangle with exclamation mark returns, it means that you are chatting to somebody who you have not yet authenticated. This can happen when your contact moves to another device with another encryption key (another installation of Jitsi, or another OTR enabled program, etc.). In this case you will need to re-authenticate each other again to be sure of the identity of person with whom you communicate.</p>
<p><strong>How to encrypt your Facebook voice calls</strong></p>
<p>Jitsi offers voice and video chats which can be independently encrypted with open standard called ZRTP. In order to initiate the chat you need to:</p>
<p><strong>Step 1:</strong> Click on the contact in Jitsi contact list and click on the voice (second icon from the left under the contact&#39;s name) or video (third) icon - see figure 5 above. A new window will appear indicating that Jitsi is establishing the connection:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-42.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-42.png</a></p>
<p>Your contact will see incoming call notification:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-43.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-43.png</a></p>
<p><strong>Step 2:</strong> If your contact accepts the call you will receive information that you are connected:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-44.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-44.png</a></p>
<p>Note the red open padlock. This means that your call is not yet encrypted with ZRTP.</p>
<p><strong>Step 3:</strong> Wait... Your and your contact&#39;s programs are establishing an encrypted connection, which may take a moment. If they succeed you will see the letters zrtp appear against an orange backgrond with a closed padlock like below. If they don&#39;t succeed in establishing a connection, you still can chat but without encryption. You can disconnect, restart Jitsi and try again to see if this time the programs will connect with encryption. ZRTP may not work in calls between accounts from different providers (such as between Google and Jit.si).</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-45.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-45.png</a></p>
<p><strong>Step 4:</strong> Observe the section under the letters zrtp and padlock with the message &quot;Compare with partner&quot; followed by 4 characters. Read these letters to your contact and ask if she sees the same characters. If she does, it means that your communication is encrypted and nobody is interfering with it. You can click Confirm. The orange zrtp field will turn green:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-46.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-46.png</a></p>
<p><strong>Step 5:</strong> You may close the black confirmation section of the window by clicking on the white x sign on upper-right part of the black section:</p>
<p><a href="https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-47.png">https://securityinabox.org/sites/siabnext.ttc.io/files/media/jitsi-en-win-47.png</a></p>
<p>Jitsi lets you voice and video chat with more than one person. Note that with this communication, ZRTP encryption can be engaged between initiator of the call and other parties, but not between parties themselves.</p>

***
***<ul>
<li><a href="safe-social-networks-who-can-access">Who can access the information I am putting online?</a></li>
<li><a href="safe-social-networks-who-controls">Who controls and owns the information I put into a social networking site?</a></li>
<li><a href="safe-social-networks-what-is-shared">What information about me are my contacts passing on to other people?</a></li>
<li><a href="safe-social-networks-consent">Will my contacts mind if I share information about them with other people?</a></li>
<li><a href="safe-social-networks-establishing-trust">Do I trust everyone with whom I&#39;m connected?</a></li>
</ul>

***