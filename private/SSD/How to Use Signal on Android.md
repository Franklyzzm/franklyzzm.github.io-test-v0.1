# How to: Use Signal on Android

Signal is a free and open source software application for Android, iOS, and Desktop that employs [end-to-end encryption![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/end-end-encryption), allowing users to send end-to-end encrypted group, text, picture, and audio & video messages, and have encrypted phone conversations between Signal users. Although Signal uses telephone numbers as contacts, encrypted calls and messages actually use your [data![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/data) connection; therefore both parties to the conversation must have Internet access on their mobile devices. Due to this, Signal users don’t incur SMS and MMS fees for these types of conversations. On Android, Signal can replace your default text messaging application, so within Signal it is still possible to send unencrypted SMS messages. Unencrypted SMS messages go through your mobile plan and may incur fees as set by your plan.

**Download Location**: The app can be downloaded from the [Google Play store](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms)

**System requirements**: Android 4.0 and up

**Version used in this guide**: Signal 4.18.3

**License**: GPLv3

**Other reading**:

* https://signal.org/
* https://support.signal.org/
* https://signal.org/blog/

**Level**: Beginner-Intermediate

**Time required**: 15-20 minutes

**Last reviewed**: 2019.12.23

 

[toc]

How to: Use Signal on Android

Installing Signal on your Android phone

Step 1: Download and Install Signal

Step 2: Register and Verify your Phone Number

Step 3: Choose a Profile Name and Avatar

Step 4: Set Signal as your default SMS app

Using Signal

How to Send an Encrypted Message

How to Initiate an Encrypted Call

How to Initiate an Encrypted Video Call

How to Start an Encrypted Group Chat

Mute Conversations

How to Verify your Contacts

Disappearing Messages



## Installing Signal on your Android phone

### Step 1: Download and Install Signal

On your Android device, enter the Google Play store and search for “Signal.” Find [Signal Private Messenger](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) and tap "Install."

After Signal has finished installing, tap “Open” to launch the app.

### Step 2: Register and Verify your Phone Number

Once you've opened the app, Signal may request access to your contact list and media files.

![img](https://ssd.eff.org/files/2018/05/09/permission_contacts_files.png)

You can tap "continue" and Signal will lead you through granting these permissions, one by one. If you deny the permissions, Signal may ask for them later.

You will now see the following screen. Enter your mobile phone number and tap “Register.”

![img](https://ssd.eff.org/files/2018/05/09/enter_phone_number_0.png)

At this time, you'll be prompted to allow Signal to view SMS messages. This allows Signal to verify your phone number more easily. You can deny this permission by tapping "Continue" and then "Deny," or allow it by tapping "Continue" and then "Allow." If you deny this permission, you can complete the setup by manually entering a six-digit code that will be sent to you via an SMS text message.

![img](https://ssd.eff.org/files/2018/05/09/permission_sms.png)

Once you enter or allow Signal to read your SMS code, your registration will be complete.

![img](https://ssd.eff.org/files/2018/05/09/enter_code.png)

![img](https://ssd.eff.org/files/2018/05/09/enter_code_check.png)

### Step 3: Choose a Profile Name and Avatar

The avatar and profile name you choose will be shown to any contacts you have saved in your address book, when you initiate new conversations, and when you explicitly allow contacts or groups to see this information. Enter any relevant information in this step and tap "Finish," or skip this step by tapping "Set later" at the bottom.

![img](https://ssd.eff.org/files/2018/05/09/profile_setup_0.png)

### Step 4: Set Signal as your default SMS app

After this process is complete, you'll see the following screen.

![img](https://ssd.eff.org/files/2018/05/09/conversations_screen.png)

By tapping "Use as default SMS app," you can have the Signal app handle both Signal as well as SMS messages. This is useful if you want to keep all your messages in one place.

Be aware that if you decide to use Signal as your default SMS app, messages sent to contacts that do not have Signal installed (even if you send them from within the Signal app) will not be encrypted.

 

## Using Signal

In order to use Signal, the person that you are contacting must have Signal installed. If you try to send a message to someone using Signal and they do not have the Signal app installed, it will send a standard, non-encrypted text message. If you try to call the person, it will place a standard phone call.

Signal provides you with a list of other Signal users in your contacts. To do this, [data![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/data) representing the phone numbers in your contact list is uploaded to the Signal servers, although this data is deleted almost immediately.

### How to Send an Encrypted Message

Note that Open Whisper Systems, the makers of Signal, use other companies' infrastructure to send its users alerts when they receive a new message. They use Google on Android and Apple on iPhone. That means information about who is receiving messages and when they were received may leak to these companies.

To get started, tap the pencil icon in the lower-right corner of the screen.

![img](https://ssd.eff.org/files/2018/05/09/compose_1.png)

You will see a list of all the registered Signal users in your contacts.

![img](https://ssd.eff.org/files/2018/05/09/list_contacts_0.png)

You can also enter the phone number of a Signal user who isn’t in your contacts. When you select a contact, you'll be brought to the text-messaging screen for your contact. Note that for Signal users, you'll see the text "Signal Message" - this means that the message will be encrypted. On this screen, the "phone" icon in the upper right corner will indicate that you can make an encrypted voice call using Signal as well. From this screen, you can send end-to-end encrypted text, picture, audio & video messages, and files.

![img](https://ssd.eff.org/files/2018/05/09/text_message_screen_0.png)

For users that do not have Signal installed, you'll see the text "Unsecured SMS," meaning the message will not be encrypted. On this screen, the "phone" icon in the upper right corner of the screen will initiate a regular, unencrypted phone call.

![img](https://ssd.eff.org/files/2018/05/09/insecure_text_message_screen.png)

### How to Initiate an Encrypted Call

To initiate an encrypted call to a contact, select that contact and then tap on the phone icon. You’ll know that the contact can accept Signal calls if you see a small padlock icon next to the phone icon.

![img](https://ssd.eff.org/files/2018/05/09/text_message_screen_phone_0.png)

Once a call is established, your call is encrypted.

### How to Initiate an Encrypted Video Call

To make an encrypted video call, simply call someone as described above. You may have to allow Signal to access your camera and microphone.

![img](https://ssd.eff.org/files/2018/05/09/permission_video_microphone.png)

Next, tap the video camera icon.

![img](https://ssd.eff.org/files/2018/05/09/ringing_screen_with_video_circled.png)

This shares your video with your friend (your friend may have to do the same).

![img](https://ssd.eff.org/files/2018/05/09/video_call_0.png)

### How to Start an Encrypted Group Chat

You can send an encrypted group message by tapping the compose icon in the lower-right corner of the screen, then tapping the overflow icon (the three dots in the upper-right corner of the screen) and selecting “New group.”

![img](https://ssd.eff.org/files/2018/05/09/compose_2.png)

 

![img](https://ssd.eff.org/files/2018/05/09/group_chat_overflow_new_group.png)

On the following screen, you'll be able to name the group and add participants to it.

![img](https://ssd.eff.org/files/2018/05/09/group_chat_name_group.png)

![img](https://ssd.eff.org/files/2018/05/09/group_chat_add_people_0.png)

After adding participants, you can tap on the check mark in the upper left corner of the screen. This will initiate the group chat.

![img](https://ssd.eff.org/files/2018/05/09/group_chat.png)

If you wish to change the group name, icon, or add participants, this can be done from the group chat screen by tapping the overflow icon (the three dots in the upper-right corner of the screen) and selecting “Edit group.”

### Mute Conversations

Sometimes conversations can be distracting. One feature that is especially useful for group chats is muting notifications, so you don't see a new notification every time a new message is written. This can be done from the group chat screen by tapping the overflow icon (the three dots in the upper-right corner of the screen) and selecting “Mute notifications.” You can then select how long you'd like the mute to be active for. This can be applied to individual conversations as well, if desired.

### How to Verify your Contacts

At this point, you can verify the authenticity of the person you are talking with to ensure that their [encryption key![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/encryption-key) wasn't tampered with or replaced with the [key![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/key) of someone else when your application downloaded it (a process called [key verification![img](https://ssd.eff.org/sites/all/themes/ssd/img/info.png)](https://ssd.eff.org/en/glossary/key-verification)). Verifying is a process that takes place when you are physically in the presence of the person you are talking with.

First, open the screen where you are able to message your contact, as described above. From this screen, tap the overflow icon (the three dots in the upper-right corner of the screen) and select "Conversation settings."

![img](https://ssd.eff.org/files/2018/05/09/tb_conversation_settings.png)

From the following screen, tap "View safety number."

![img](https://ssd.eff.org/files/2018/05/09/tb_view_safety_number.png)

You will now be brought to a screen which displays a QR code and a 'safety number.' This code will be unique for every different contact you are conversing with. Have your contact navigate to the corresponding screen for their conversation with you, so that they have a QR code displayed on their screen as well.

![img](https://ssd.eff.org/files/2018/05/09/safety_number_screen_0.png)

Back on your device, you can tap on your QR code, which will use the camera to scan the QR code that is displayed on your contact's screen. Align your camera to the QR code:

![img](https://ssd.eff.org/files/2018/05/09/safety_number_scan.png)

Hopefully, your camera will scan the QR code and display a check mark, like this:

![img](https://ssd.eff.org/files/2018/05/09/safety_number_matches_0.png)

This indicates that you have verified your contact successfully. You should now tap the slider next to "Verified" to have the app remember that your contact has been verified. If instead your screen looks like this, something has gone wrong:

![img](https://ssd.eff.org/files/2018/05/09/safety_number_failed_0.png)

You may want to avoid discussing sensitive topics until you have verified keys with that person.

*Note for power users: The screen displaying your QR code also has an icon to share your safety number in the top-right corner. In-person verification is the preferred method, but you may have already authenticated your contact using another secure application. Since you've already verified your contact, you can safely use the trust established in that application to verify numbers within Signal, without having to be physically in the presence of your contact. In this case you can share your safety number with that application by tapping the "share" icon and sending your contact your safety number.*

### Disappearing Messages

Signal has a feature called "disappearing messages" which ensures that messages will be removed from your device and the device of your contact some chosen amount of time after they are seen.

You do not have control over the person with whom you are chatting—she could be logging or taking screenshots of your conversation, even if you've enabled "disappearing messages."

To enable "disappearing messages" for a conversation, open the screen where you are able to message your contact. From this screen, tap the overflow icon (the three dots in the upper-right corner of the screen) and select "Disappearing messages."

![img](https://ssd.eff.org/files/2018/05/09/tb_disappearing_messages_0.png)

A new screen will appear that allows you to choose how quickly messages will disappear:

![img](https://ssd.eff.org/files/2018/05/09/tb_disappearing_messages_options.png)

After selecting this option you should see information in the conversation indicating that "disappearing messages" have been enabled.

![img](https://ssd.eff.org/files/2018/05/09/tb_disappearing_messages_enabled_0.png)

You can now send messages with the assurance that they will be removed after the chosen amount of time.

