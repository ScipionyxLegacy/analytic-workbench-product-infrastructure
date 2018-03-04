#Provides
This component provides the following services:
- Zuul Gateway
- Authorization Server


#Authorization Server
End points for the Authorization Server:
* /oauth/authorize 
* /oauth/authorize,	methods=[POST],		params=[user_oauth_approval]
* /oauth/token,		methods=[GET]
* /oauth/token,		methods=[POST]
* /oauth/check_token
* /oauth/confirm_access
* /oauth/error 

##References
- http://www.swisspush.org/security/2016/10/17/oauth2-in-depth-introduction-for-enterprises
- https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-security.html
- https://stackoverflow.com/questions/45579623/what-the-configuration-of-spring-security-oauth2-authorizedgranttypes-means-in-p