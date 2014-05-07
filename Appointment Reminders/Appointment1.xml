<dialplan name="SimpleApptIVR1">
    <!--(c) copyright 2013 CallFire.com -->
    <!--Author: Jeff Spisak-->
    <!--For information support@callfire.com-->
    <!--This sample script is provided as is-->
    <!--with no warranties of applicability expressed or implied-->
    <amd>
        <live>
            <play type="tts" voice="female2">This is A B C Taxes calling to remind
                ${contact.firstName} ${contact.lastName} of a tax preparation
                appointment scheduled for ${contact.C} at ${contact.D}. The appointment
                is located at ${contact.E}. If you need to cancel or reschedule this
                appointment, please stay on the line for assistance.</play>
            <transfer callerid="${call.callerid}">
                2135551212 
            </transfer>
            <hangup/>
        </live>
        <machine>
            <play type="tts" voice="female2">This is A B C Taxes calling to remind
                ${contact.firstName} ${contact.lastName} of a tax preparation
                appointment scheduled for ${contact.C} at ${contact.D}. The appointment
                is located at ${contact.E}. If you need to cancel or reschedule this
                appointment, please call back at 2 1 3, 5 5 5, 1 2 1 2 for
                assistance.</play>
            <hangup/>
        </machine>
    </amd>
</dialplan>
