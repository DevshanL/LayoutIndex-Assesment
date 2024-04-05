# LayoutIndex-Assesment
This sample project is managing locations that control multiple devices.
Your task is to create a REST service and User interfaces for storing information
about these locations and their associated devices. This information must be
stored in the database. When storing a location or device, you should add
necessary validations.
The solution must also offer an operation for displaying location details about
all stored locations and an operation for displaying details for single location
with their devices. Finally it must be possible to add and remove a device from
a location.

Each Location has
 Human readable name (string) *
 Address (string)
 Phone (string)
 Multiple associated devices
Each device has
 An unique serial number (string) *
 Type - (pos/kisok/signage) *
 Image *
 Status - active/inactive
*(required)
