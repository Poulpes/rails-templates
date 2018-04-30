# Rails Templates

## Minimal

Get a minimal rails 5.1+ app ready to be deployed on Heroku with Simple form and
debugging gems.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/poulpes/rails-templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

## Devise

Same as minimal **plus** a Devise install with a generated `User` model.


```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/poulpes/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```