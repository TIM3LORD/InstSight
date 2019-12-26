# InstSight

This is a demo project using the instagram_private_api by Github user ping.

As of right now this project is CLI based but can be easily converted into a REST API.

InstSight lets you find photos of private users by searching another public user who is likely to have images of the private user.

InstSight first checks the photos of the public user to find any images the private user may be tagged in. It then recursively checks the photos of each of user in the specified public user's followers list.

This search can be made more precise by searching the profile of other users who are tagged in the same image that the private user is tagged in.
