<strong>Utilities</strong>

AccountVerification

This IVR is used to capture a five-digit number, which it then sends to your company's website for verification. Typically, this would be a .php page that you set up on your server. Your server's response is captured (the response is usually True or False), then sent back to the IVR. You can configure the XML to continue according to the response.

AfterHoursIfTag

This code is used to direct called based on the time or the day of the week, or both.

NestedVariables

The point of nested variables is to allow you to define all your choices at the start of the IVR, then use nested variables to have the XML read them. It is a time-saver; the same result can be accomplished with individual variables.

Password

This requires a caller to enter a password before continuing. It could be placed at the start of an inbound IVR in order to restrict access.

ScreenCallerID

This rejects blocked, restricted, unknown, and anonymous calls. It instructs callers to call back with their caller ID unblocked.

SendSMS

Similar to the SplitJoin, this asks callers to enter a phone number. It then confirms the number, and sends it a text message.

SimpleTransfer1

This outbound IVR hangs up on answering machines. For live answers, it greets the recipient by name and then transfers them to the office.

SimpleTransfer2

Most commonly used as an inbound IVR, this asks callers to press one for sales and two for support. The call is transferred, and transfers to voice mail if no one answers after five rings.

SplitJoin

Use this code to break up phone numbers or other long numbers. The text to speech in the CallFire XML reads all numbers as integers, so it would interpret a standard US phone number (213.221.2231) as two trillion, one hundred thirty-two million, two hundred twelve, two hundred thirty-one. The split/join commands breaks up the numbers individually and reads them back one at a time. This is also useful for street numbers and ZIP codes.

TimeoutCounter

This IVR incorporates a Setvar and an If tag to count the number of times a user executes the Timeout function. Each time this is triggered, the value of the Setvar increases by one. At a given threshold, the If tag will announce that the maximum number of attempts has been reached, and terminate the call. 

TransferByDay

This inbound IVR was requested by a client who needed the calls transferred based on the day of the week. If no one answers the call, and during the weekends, the call is directed to a voice mail module.
