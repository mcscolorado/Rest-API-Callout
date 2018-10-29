# VehicleVerification
VIN verification and gather vehicle details

AccountTrigger - When Account is created or Updated - Make a United Express callout to create user

UnitedDeliverServices - Make Rest API callout and create user in United Express if Account is 'Active' And Account external driver number is blank or null. If API callout results in error save the error on a field on Account

UnitedDeliverServicesTest - Test Call

MockHttpUDSResponseGenerator - Mock response generator
