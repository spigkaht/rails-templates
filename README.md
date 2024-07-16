# rails-templates
Rails templates for personal use; default and with devise

NOTE: Substantial portions of templates have been copied from Le Wagon's Rails templates
... SEE LICENSE for details

⚠️ The following templates have been made for Rails 7. If you use Rails 6, please refer to the no-update branch templates

Default
Get a minimal rails app ready to be deployed on Heroku with Simple form and debugging gems.

rails new \
  -d postgresql \
  -m https://raw.githubusercontent.com/spigkaht/rails-templates/main/default.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME

Devise
Same as default plus a Devise install with a generated User model.

rails new \
  -d postgresql \
  -m https://raw.githubusercontent.com/spigkaht/rails-templates/main/devise.rb \
  br-app \
  --css tailwind

TAILWIND CSS
Append --css tailwind to the command chain
