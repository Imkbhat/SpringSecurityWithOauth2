# SpringSecurityWithOauth2
SpringSecurityWithOauth2

To configure your application in google, follow the below steps:
    Open Google Console API
    Click on “New Project” button at the top left of the page.
    Set a name for your project then click “Create”.
    Now your application is created, choose your application from the list of projects at the top toolbar, then choose “APIs & Services” -> “Credentials” from the left menu.
    Click “Create Credentials” -> “OAuth Client Id” then choose your application type, in this tutorial we choose “Web Application”
    Add your redirect URI under “Authorized redirect URIs” text box, this is the URL which google uses when redirecting back to your application after successful authentication.
    Click on “Create”.

Reference Used : https://www.programmergate.com/spring-boot-spring-security-oauth2/
