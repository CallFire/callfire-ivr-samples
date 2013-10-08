<strong>Appointment Reminders</strong>


<a href="https://github.com/CallFire/callfire-ivr-samples/blob/develop/Appointment%20Reminders/Appointment1.xml">Appointment1</br>

In this IVR, there are two defined messages: one for answering machines, and one for live answers. The only difference is that the live message invites recipients to stay on the line to be transferred to the office. This would be useful for those wishing to cancel or reschedule appointments.

The message is personalized using a combination of CallFire system variables. ${contact.firstName} and ${contact.lastName} will read the appropriate contact information from your database of CallFire contacts. Also included are variables such as ${contact.x}, where x represents a column in the Excel file of contacts uploaded into this particular IVR campaign. We have used columns C, D, and E to specify, respectively, the date, time, and address of the appointment.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/develop/Appointment%20Reminders/Appointment2.xml">Appointment2</br>

In this example, we have included the option for recipients to opt out of future communications. In the live answer message, the recipient is asked to indicate via keypress whether or not he is attending the meeting. There is also an option to be added to the CallFire Do Not Call (DNC) list. All responses are recorded, and if the DNC option is selected, the recipient will be immediately added to the DNC list. In the answering machine message, the meeting time and place is announced, and a phone number is provided for those to call in order to obtain additional information.

<a href="https://github.com/CallFire/callfire-ivr-samples/blob/develop/Appointment%20Reminders/AppointmentConfirmation%201.xml">AppointmentConfirmation</br>

Here
