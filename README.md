# Github API Js

## Requirements

Using the HTML/CSS included in this repo add javascript needed to load the following:

- Your profile: `https://api.github.com/users/<username>`
- Your repos: `https://api.github.com/users/<username>/repos`

After loading data from the Github API, write at least the following information to the DOM:

- name
- blog
- location
- email
- an `<img>` with its source as the avatar_url
- html_url
- for each repo owned by your user, list that repo in a `<ul>`

### Important Note
Github api has a hard rate limit of 60 per HOUR if the user is unathenticated.  Create a Personal Access Token (under personal settings).  Then use basic auth where
your github username is the username and the token is the password.  You can find how to add the header to the ajax call [here](http://stackoverflow.com/questions/5507234/how-to-use-basic-auth-and-jquery-and-ajax)

## Resources
* [Github Repo](https://github.com/tiy-lv-java-2016-06/github-api-js)
* [Javascript Guid](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
* [Document Object](https://developer.mozilla.org/en-US/docs/Web/API/document)
* [Using JQuery Core](https://learn.jquery.com/using-jquery-core/)
