#  Single Sign-On with Spring Security OAuth2 and GitHub, Google, Facebook:

## "Social" login: (delegate to GitHub), include the Spring Security OAuth 2.0 Client starter,
# it will secure your app with OAuth 2.0 by default:


Spring manages OAuth flow with GitHub automatically.
No JWT decoder needed because GitHub tokens are opaque.
No need to implement a UserDetailsService because GitHub provides user details.

https://spring.io/guides/tutorials/spring-boot-oauth2

Next, you need to configure your app to use GitHub as the authentication provider. To achieve this, do the following:

Add a New GitHub app

Configure application.yml

Boot up the application


