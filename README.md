[![Build Status](https://travis-ci.org/yeti/YAK-server.svg?branch=master)](https://travis-ci.org/yeti/YAK-server)

YAK-server
=======================

Server-side implementation of Yeti App Kit built on Django. Includes:

- `rest_core`: Base features to support other REST libraries, including test cases and permissions.
- `rest_user`: User relevant API resources for creating and authenticating users with OAuth2.0
- `rest_social_auth`: Implements social sign up with python social auth
- `rest_social_network`: Models and APIs for social functionality (hashtags, likes, following, comments, @mentions, flagging / reporting)
- `rest_notifications`: Models and APIs for notifications. Includes support for push notifications with Pushwoosh.

Our REST libraries are all built with Django REST Framework. They were originally ported (and since improved upon) from earlier Yeti libraries `manticore-tastypie-core`, `manticore-tastypie-user`, `manticore-tastypie-social`, and `manticore-tastypie-notifications` primarily authored by [@rmutter](https://github.com/rmutter).
# jew-server
