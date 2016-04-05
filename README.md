# A starting point for our rails apps / stack

# Servers
- Puma for Development
- Passenger (Apache/Nginx) for Prod

# DB
- PostgresSQL

# Template
- Haml

# Testing
- Respec w/ Capybara

# Frontend
- Choice 1: BootStrap (Default)
- Choice 2: Semantic UI

*Both should include Manhattan (Our grid)*
*These can all be included via bower*

# Subscriptions
- Koudoku (Y/N)

# Payments
- Stripe (Y/N)

# Analytics
- GA
- Mixpanel

# Ban Spiders
- Dev/Staging only ( Is there a gem for this? )

# Create a github project
- Yes

# RVM
- No

# Email
- Mailgun

# Authentication
- Devise
- OmniAuth

# Authorization
- CanCanCan

# FormBuilder
- SimpleForm

# StarterApp
- Custom / Kohactive
- Include a services dir
- Include a serializer dir

# Image Storage
- Cloudinary
- Carrierwave/S3

# JS
- Angular (Y/N) - Generates structure in js/assets & includes angular stuff in bower

# Extra Gems
- versionist
- active-model-serializers
- BetterErrors (dev/test)
- Binding of Caller (dev/test)
- Bower
- guard (dev/test)
- guard-bundler (dev/test)
- guard-rails (dev/test)
- guard-rspec (dev/test)
- quiet_assets (dev/test)
- factory_girl_rails (dev/test)
- faker (dev/test)
- pry-rails (dev/test)
- pry-rescue (dev/test)
- rspec-rails (dev/test)
- database_cleaner (test)
- rails_12factor (prod only)
