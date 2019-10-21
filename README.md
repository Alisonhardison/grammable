# Grammable
An Instagram clone that was built using industry-standard, test-driven development following numerous red/green/refactor cycles.
This app is viewable here https://grammable-alison-hardison.herokuapp.com

## Implementation Details:
 - Built on Ruby on Rails framework
 - PostgreSQL database
 - Twitter Bootstrap 3 for CSS and UI components
 - Simple Form gem for form implementation
 - Devise gem for user authentication (customized to allow :username at sign up & save to DB)
 - CarrierWave gem for image and video uploading & Amazon Web Services (S3) for photo/video storage
 - MiniMagick for image resizing on upload
 - TDD using RSpec & FactoryBot gems
 - Responsive design

## Production Deployment
  $ heroku create grammable-alison-hardison

  $ git push heroku master
  
## Support
  Bug reports and feature requests can be filed with the rest for the Ruby on Rails project here: 
  https://github.com/Alisonhardison/grammable/issues

