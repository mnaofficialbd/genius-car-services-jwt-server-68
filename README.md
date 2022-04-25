## Genius Car Services JWT Server Side 

### Live project link : https://genius-car-services-79706.web.app/

### Client Side Repository: 
- https://github.com/mnaofficialbd/genius-car-services-jwt-client-68

#### Install Package (Mongodb)
- express
- cors
- mongodb
- dotenv
- JWB (JSON Web Token)

## Server deploy steps:
-  `One time for one account or pc`
1. Create heroku account (signup.heroku.com).
2. verify email.
3. install heroku CLI / install heroku in pc.
4. heroku login (this command use in server project terminal)

- `For each project one time`
1. heroku create. (cmd command )
2. Make sure you: git add . git commit . git push
3. git push heroku main (cmd command)
4. Go to heroku dashboard > Current project > Settings > Reveal Config Vars 
5. Copy paste config vars from server-project-folder > .env file.
6. Make sure you have whitelisted all ip address to access mongodb.

- `Update server`
1. Make changes.
2. Make sure you: git add . git commit . git push.
3. git push heroku main (cmd command).

- `Connect Server with Client side project and deploy client project`
1. replace localhost url by heroku url / link.
2. npm run build (cmd command in client side project).
3. firebase deploy.