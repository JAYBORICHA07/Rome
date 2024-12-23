




So in this blog we will be covering how does whatsApp handles end to end encryption. so let us assume 

So whatsApp does not save any of the user data on it's server but what it does is that it stores the user data in the user's phone/local device in form of decrypted data and does not send any data to the whats app servers.

By doing this now whatsApp does not need to handle/store the user data on the server and as the data is in the user's device.

The above explanation is understandable for one-to-one chat or peer-to-peer chat but what about group chats? where different users are sending the messages to one common group and everyone is able to see each other's message.

So let us assume a whatsApp group where there are three members in that group Jay, Karan and Krishna. When ever any one of the member sends a message in the group that message will be stored separately in each of the member's device. Like if Jay sends message "Hi" then this message will be stored in the each of the group member's device. This is how whatsApp handles group messages. If the groups message data found in the user's storage then it will considered as part of group else user won't be able to see those messages.

![[Pasted image 20241223111342.png]]


Now we also have option for cloud backup which is there in the whatsApp to sync the data so in that case whatsApp uses asymmetric encryption so it encrypts your data with your pubic key and stores the data on the cloud which can only be decrypted by your private key which will be on your device only and then when you need backup then your data will be available to you from cloud.

In case of whatsApp web when we can the QR code on browser from our device, whatsApp sends devices mobile number and credentials/Keys to the whatsApp web and it sync your account from there.