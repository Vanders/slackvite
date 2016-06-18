# Slackvite
An email form for Slack community invitations

### Installation
```
gem install slackvite
```

### Usage
In your controller:
```
email = 'matt@roseware.io'
slackvite = Slackvite::Configuration.new('your-token')
slackvite.sendTo(email)
```
