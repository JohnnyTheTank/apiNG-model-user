Universal **_USER_** [model](https://aping.readme.io/docs/models) for [apiNG](https://github.com/JohnnyTheTank/apiNG)

# Supported apiNG Plugins
- [x] **GitHub** ([apiNG-plugin-github](https://github.com/JohnnyTheTank/apiNG-plugin-github))

# JavaScript
```JavaScript
var user = {
    platform: undefined, //NAME of platform ( "flickr" / "facebook", "instagram" , ...)
    username: undefined, //NAME of of the user
    first_name: undefined, //first name
    last_name: undefined, //last name
    user_id: undefined, //ID of user (channel / page / account, ...)
    user_url: undefined, //url to user (channel / uploader / page / account, ...)
    intern_id: undefined, // INTERN ID of user (facebook id, instagram id, ...)
    thumb_url: undefined, // best case 200px (min)
    thumb_width: undefined,
    thumb_height: undefined,
    img_url: undefined, //preview image url (best case 700px)
    img_width: undefined,
    img_height: undefined,
    native_url: undefined, // best quality
    native_width: undefined,
    native_height: undefined,
    source: undefined, //different payload
};
```

# JSON

```JSON
{
    "platform": false,
    "username": false,
    "first_name": false,
    "last_name": false,
    "user_id": false,
    "user_url": false,
    "intern_id": false,
    "thumb_url": false,
    "thumb_width": false,
    "thumb_height": false,
    "img_url": false,
    "img_width": false,
    "img_height": false,
    "native_url": false,
    "native_width": false,
    "native_height": false,
    "source": false
}
```