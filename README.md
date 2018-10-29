# Create user in external system

AccountTrigger - When Account is created or Updated - Make a United Deliver Services callout to create user

UnitedDeliverServices - Make Rest API callout and create user in United Express if Account is 'Active' And Account external driver number is blank or null. If API callout results in error save the error on a field on Account

UDS__c - Custom settings to keep United Delivery Services credentials

UnitedDeliverServicesTest - Test Call

MockHttpUDSResponseGenerator - Mock response generator
