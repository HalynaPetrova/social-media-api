# Social Media API

The RESTful API for a social media platform. 


## User Registration and Authentication
- User can register with his email and password to create an account.
- User can login with his credentials and receive a token for authentication.
- User can logout and invalidate his token.

## User Profile
- The user can create and update his profile, including his profile picture, bio, and other details.
- The user can retrieve his profile and view the profiles of other users.
- The user can search for users by username or city where they live.

## Follow/Unfollow
- The user can follow and unfollow other users.
- The user can view the list of users he is following and the list of users following him.

## Post Creation and Retrieval
- The user can create new posts with text content and media attachments (e.g., images).
- The user can retrieve posts by hashtags.

## Likes and Comments
- The user can like and unlike posts. 
- The user can add comments to posts and view comments of other users.

## API Permissions
- Only authenticated users can create posts, like posts, and follow/unfollow users.
- The user can update and delete his posts and comments.
- The user can update his profile.

## API Documentation
- The API is well-documented with clear instructions on how to use each endpoint.
- The documentation includes sample API requests and responses for different endpoints.

## How to install using GitHub
- Clone this repository
- Create venv: python -m venv venv
- Activate venv: source venv/bin/activate
- Install requirements: pip install -r requirements.txt
- Run: python manage.py runserver
- Create user via: user/register
- Get access token via: user/token

## BD structure

![db_social_media](https://github.com/HalynaPetrova/social-media-api/assets/92261713/1b6a1108-02c7-454a-aec4-fc5fbc7ef70d)

