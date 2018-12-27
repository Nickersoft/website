# LimbForge Webapp

### Prerequisites
This app is built on ruby V2.2.3, rails V4.2.5, and requires a postgresql database.
See instructions [here](https://gorails.com/setup) on how to setup your environment.

### Set up
```
bundle install
rake db:create
rake db:migrate
```

### Usage
```
rails s
```

### Set up environments locally
You need a .env file for all of your variables. Here's what you need

.env file =
```
HTTP_NAME = 'somename'

HTTP_PASS = 'somepassword'

SECRET_KEY_BASE = 'blahblah'

S3_BUCKET_NAME = 'somebucketname'

RECAPTCHA_PUBLIC_KEY = 'yopublickey'

RECAPTCHA_PRIVATE_KEY = 'yoprivatekey'

AWS_ACCESS_KEY = 'yoawskey'

AWS_SECRET_ACCESS_KEY = 'yosecretawskey'

```
