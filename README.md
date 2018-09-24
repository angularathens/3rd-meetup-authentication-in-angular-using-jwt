# Authentication mechanism using JWT

Almost every app we develop requires the users to be authenticated using their credentials, and to be authorized. What about if the server authentication mechanism is based on JWT? How can we ensure that users with specific user roles are authorized to access a route?

In this topic we will examine the format of a JWT, the way we can decode it and extract the important information it has. We will see how to send the needed headers via HTTP and how to use the HTTP interceptor. Last but not least, we will see how to decide whether a user can access a route or not.
