<strong>Appointment Reminders</strong>


<a href="https://github.com/CallFire/callfire-ivr-samples/blob/develop/Appointment%20Reminders/Appointment1.xml">Appointment1</br>

In this IVR, there are two defined messages: one for answering machines, and one for live answers. The only difference is that the live messages invites recipients to stay on the line and be automatically transferred to the office. This would be useful for those wishing to cancel or reschedule appointments.

The message is personalized using a combination of CallFire system variables. ${contact.firstName} and ${contact.lastName} will read the appropriate contact information. Also included are variables such as ${contact.x}, where x represents a column in the Excel file of contacts uploaded into this particular IVR campaign. We have used columns C, D, and E to specify, respectively, the date, time, and address of the appointment.

Appointment2

AppointmentConfirmation
