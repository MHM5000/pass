# Passwords

## For Developers

+ Never store the password itself.
+ Force users to choose a longer password, not a difficult to remember password -> [xkcd.com/936/](http://xkcd.com/936/)
+ Ask your users to change their password according to importance of their account / your site on a yearly/quarterly/monthly basis.
+ Use HTTPS at least for Login/Signup/Reset and related pages.
+ Never send plain password of users to their email.
+ Double check ```chmod``` of your files and folders.
+ Your partner(designer) will use the same validation as you, but with javascript. You should run the server-side validation, too. You [can't trust](https://en.wikipedia.org/wiki/User_agent#User_agent_spoofing) user-agent.
+ Use [strong](#for-everybody) passwords for accessing the developping land! After all you are an important person.
