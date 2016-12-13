# AngularFire-Ionic-Chat

* This project is a HTML5 hybrid mobile app of real-time chatting for both mobile and web platforms.
* It's originally designed for testing the real-time feature of Firebase and the performance of Ionic on mobile plateforms.
* [Live Demo](https://matsit.firebaseapp.com/) -- Test it with your mobile devices or activate the [Device Mode & Mobile Emulation](https://developer.chrome.com/devtools/docs/device-mode) if you want to test it on web browsers.

## Tech-stack

* Generated with [yo ionic generator](https://github.com/diegonetto/generator-ionic)
* Integrated with [AngularFire](https://www.firebase.com/docs/web/libraries/angular/)
* Hosted on [Firebase Host](https://www.firebase.com/docs/hosting/)

## Features

* Authenticate users with email & password
* Chat with a individual person
* Chat with multiple persons 
* Chat with all persons
* Create the chat room
* Account information && logout

## Get started

* Fork and clone this repo
* Run `npm install && bower install`
* Run `grunt serve` for preview
* Run `grunt platform:add:ios` or `grunt platform:add:android` to add platforms
* For more command lines, please check [here](https://github.com/diegonetto/generator-ionic)
* If you want to configure your own firebase instance, you should go to app/scripts/app.js and edit the variable `firebaseUrl`. For example, `var firebaseUrl = "https://xxx.firebaseio.com/";`.

## Todo

- [ ] Authenticate users with Facebook, Twitter, GitHub or Google
- [ ] Find friends by their username or email or more methods
- [ ] Invite people to a specific chat room
- [ ] Notification for new messages
- [ ] Support more data formats for sending messages, such as link, emoji, images etc.

## License

[MIT License](https://opensource.org/licenses/MIT)

---

> [yehuang.me](https://yehuang.me) &nbsp;&middot;&nbsp;
> GitHub [@crabcanon](https://github.com/crabcanon) &nbsp;&middot;&nbsp;
> Gmail [@sysuhuangye](<mailto:sysuhuangye@gmail.com>)
