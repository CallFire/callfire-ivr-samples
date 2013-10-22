<strong>Appointment Reminders</strong>


<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Appointment%20Reminders/Appointment1.xml">Appointment1</a>

In this IVR, there are two defined messages: one for answering machines, and one for live answers. The only difference is that the live message invites recipients to stay on the line to be transferred to the office. This would be useful for those wishing to cancel or reschedule appointments.

The message is personalized using a combination of CallFire system variables. ${contact.firstName} and ${contact.lastName} will read the appropriate contact information from your database of CallFire contacts. Also included are variables such as ${contact.x}, where x represents a column in the Excel file of contacts uploaded into this particular IVR campaign. We have used columns C, D, and E to specify, respectively, the date, time, and address of the appointment.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Appointment%20Reminders/Appointment2.xml">Appointment2</a>

In this example, we have included the option for recipients to opt out of future communications. In the live answer message, the recipient is asked to indicate via keypress whether or not he is attending the meeting. There is also an option to be added to the CallFire Do Not Call (DNC) list. All responses are recorded, and if the DNC option is selected, the recipient will be immediately added to the DNC list. In the answering machine message, the meeting time and place is announced, and a phone number is provided for those to call in order to obtain additional information.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Appointment%20Reminders/AppointmentConfirmation1.xml">AppointmentConfirmation1</a>

This IVR is similar to Appointment1, except that it only intends to confirm or cancel appointments. Should recipients choose to cancel, they are instructed to call the office directly to reschedule (there is no automatic transfer). The business scenario here is to encourage confirmation of existing appointments, and to place the onus of rescheduling on the recipient. The answering machine message is similar to Appointment1.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/master/Appointment%20Reminders/AppointmentConfirmation2.xml">AppointmentConfirmation2</a>

This reminder has an option to send the appointment time and date to a recipient's cell phone number. The recipient can select the number that the IVR calls (indicated as ${call.phonenumber} in CallFire XML), or else choose to enter a different number. The IVR reads the number back to them and allows them to confirm or reenter it.
