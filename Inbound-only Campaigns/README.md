<strong>Inbound-only Campaigns</strong>

Note: these IVRs would only be assigned to an inbound DID (phone number) that you purchase from CallFire. 

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Inbound-only%20Campaigns/DNCHandler.xml">DNC Handler</a>

When the DID is pointed to this IVR and people call, their phone number is automatically added to your CallFire DNC list. 

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Inbound-only%20Campaigns/DNCModule.xml">DNCModule</a>

This is similar to the DNCHandler. Callers can choose to add the number they are calling from to your DNC (it is not automatic). They can also enter additional numbers to the DNC list. Finally, there is an option to leave a message. 

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Inbound-only%20Campaigns/SmallBusinessTree.xml">SmallBusinessTree</a>

This is a classic phone tree. Callers have the option to press one for sales, two for support, or to enter the extension of the party they wish to reach. The call is transferred accordingly. Should no one pick up the call, it will be passed to voicemail.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Inbound-only%20Campaigns/VoicemailModule.xml">VoicemailModule</a>

Our standard voicemail module informs callers that on one is available, and invites them to leave a message. Afterwards, the caller can save the voicemail, listen to it, and rerecord it, if desired.
