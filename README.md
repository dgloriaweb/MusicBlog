# Music Blog
## The site has a normal laravel backend
- must have email validation
- database just like a blog
- create slug urls for blog posts
- store blog post creators (later used by members)
- remove any link or url or other malicious code from blog posts
## The users can comment on blogs and can collect points, but non-users can also read the posts and the comments
- Encourage users by donating them badges based on their comments
- set user levels by ading isEditor
- store badges for users somewhere in the users table, eg. use an  int from 1-9 based on the expert level of the user. Eg user_level
- Enable users with badges to create content
## Fit all GDPR requirements - provide data when needed, don’t store anything apart from email and username
## Create figma design, follow blog designs