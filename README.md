# netlify-okta

This is a boilerplate solution for using OKTA CpenID Connect to authenticate an OKTA user. It has a public and secure content.

it uses netlify-lambda as middleware.

Hosted on URL: https://mystifying-lamport-8956dc.netlify.app/

rimraf for cleaning.

    "dev": "rimraf dist && parcel client/index.html",
    "build": "rimraf dist && netlify-lambda install && parcel build client/index.html"
