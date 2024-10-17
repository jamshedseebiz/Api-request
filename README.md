                                                         GET :

When you open your Facebook news feed, a GET API request is used. You are retrieving data like your 
friends posts, comments, and updates from the server. You're only viewing the information without
 creating  updating anything.

Example: When you refresh your news feed, all the posts are loaded onto your screen via a GET request.

                                                        POST:
When you post a new status, upload a photo, or comment on something, a POST request is used. This sends
 new information to the server and creates a new resource.

Example: You write a status update like "Feeling Happy" and post it. A POST request creates this new post on the server.

                                                        PUT:

The PUT method is used to completely replace an existing resource. This means the old data is fully replaced
 with new information.

If you're editing your entire Facebook profile details (name, address, email) at once, the PUT method would
 replace the entire profile with the updated data.

                                                       PATCH:

The PATCH method is used to partially update a resource, meaning you only change some fields 
without replacing the entire resource.

If you are only updating your email address on your profile but leaving the other details unchanged, 
the PATCH method would be used to update just that specific part.

                                                     DELETE:

 The DELETE method is used to permanently remove a resource from the server.

If you delete an old post on Facebook, the DELETE request will permanently remove that post from the server.

