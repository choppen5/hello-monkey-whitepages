#Twilio Client WhitePages demo.

This is a demo of Twilio client that is mostly based on the standard Twilio Client quickstart guide seen here: https://www.twilio.com/docs/quickstart/ruby/client/hello-monkey


The changes to the "hello monkey" code include:
- New layout for showing caller info
- Including the Whitepages API in the server layer to show caller info

To get it running, you have to do the following:
- Same Twilio setup requirments as detailed here: https://www.twilio.com/docs/quickstart/ruby/client/hello-monkey
- (including creating an application id)
- Register as a developer at http://pro.whitepages.com/developer/

Once set up, to run this locally, you need the follwing evnironment variables (or hard code the variables) as seen in server.rb

- caller_id   = ENV['twilio_caller_id']
- account_sid = ENV['twilio_account_sid']
- auth_token  = ENV['twilio_auth_token']
- appsid      = ENV['twilio_app_id']
- api_key     = ENV['whitepages_api_key'] 


Ruby steps:
- Bundle install
- ruby server.rb







