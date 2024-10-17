                                                         GET API:

If you have a GET API, you can use it to obtain data from a server, but you cannot create, update,
 or delete data. In this method, you are simply requesting information from the server.
  The approach is stateless, meaning each request is independent, but it still requires 
  a request to the server to retrieve data.

Real Life Example:
When you visit a weather website to check the current weather in your city, the backend uses 
a GET request. You are only asking for information from the server without creating or updating any data.

                                                        POST:

 The POST method is used to create new resources on the server, such as adding a new entry or record.

Real Life Example:
When you write a new blog post and publish it on a website, a POST request is sent to the server to create the new post.
 Pressing the submit button sends the data to the server.

                                                        PUT:

The PUT method is used to completely replace an existing resource. This means the old data is fully replaced
 with new information.

Real Life Example:
If you're editing your entire Facebook profile details (name, address, email) at once, the PUT method would
 replace the entire profile with the updated data.

                                                       PATCH:

The PATCH method is used to partially update a resource, meaning you only change some fields 
without replacing the entire resource.

Real Life Example:
If you are only updating your email address on your profile but leaving the other details unchanged, 
the PATCH method would be used to update just that specific part.

                                                     DELETE:

 The DELETE method is used to permanently remove a resource from the server.

Real Life Example:
If you delete an old post on Facebook, the DELETE request will permanently remove that post from the server.

