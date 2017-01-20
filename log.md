# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress**: ngResource, Angular Form Validation, user prompting with Bootstrap help-block

**Thoughts**: retreive data from back-end(RESTful API) via ngResource, disable HTML5 form validation, use ng-class/ng-show to promting user.

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 7
___
### Day 1: January 4, 2017

**Today's Progress**: ngResource $save, CORS

**Thoughts**: send comment with $resource().$save(), support CORS with module(cors), not simple request will have a OPTIONS request as CORS prefilght to get the support server CORS methods, redirect from HTTP to HTTPS when CROS prefilght will cause invalid.

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 32
___
### Day 2: Januray 5, 2017

**Today's Progress**: Nginx, Express sercurity SSL certificate with Let's encrypt SSL

**Thoughts**: 
HTTPS on whole site, solution 
1. Nginx force HTTPS, backend http visit(backend no need get ssl cert/keys).
2. Nginx force HTTPS, backend https(Nginx proxy to backend https visit, it fails when need CORS but express have redirected http -> https)

[Client] -- HTTP/HTTPS -> [Nginx] <- HTTPS -> [Front-end]
[Front-end] -- HTTPS -> [Nginx] <- HTTPS -> [Back-end]

**Link(s) to work**: 
- [MEAN Project - HTTPS on whole site](http://www.jianshu.com/p/3cef55f0ea6f)
- [MEAN Project - HTTPS on whole site](https://github.com/kimochg/TinyThoughts/blob/master/Security/MEAN%20project%20-%20HTTPS%20on%20whole%20site.md)

**FreeCodeCamp**: 52
___
### Day 3: Januray 6, 2017

**Today's Progress**: Sign in support functional implement

**Thoughts**: 
Code can be written in both Facotry and Controller, there is maybe philosophy to do the choice. MVVM

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 52
___
### Day 4: Januray 7, 2017

**Today's Progress**: User login/logout/register Complete

**Thoughts**: 
Angular directive is of great importance in developing app, the Sign in form need to be more designed

**Link(s) to work**: 
1. [SHINO App](https://github.com/kimochg/shino)
2. [Password check directive in angularjs](http://www.jianshu.com/p/9841b3d71669)

**FreeCodeCamp**: 100
___
### Day 5: Januray 8, 2017

**Today's Progress**: 
- user can comment dish if login, corresponding to backend data form
- MongoDB enable authentication for safe risk on default configuration

**Thoughts**: 
- Mongodb have safe vulner when default configuration.
- corresponding to backend data form using RESTful API response.
- next, user session token refresh, when and where?

**Link(s) to work**: 
1. [SHINO App](https://github.com/kimochg/shino)
2. [MongoDB Enable Authentication](http://www.jianshu.com/p/79caa1cc49a5)

**FreeCodeCamp**: 119
___
### Day 6: Januray 9, 2017

**Today's Progress**: 
- token in local storage will be verified by GET /user/login, setAuthUtil when success, perform logout when fail
- final polish SHINO website: Banner css linear-gradient, google fonts for title
- strip debugger and console output, and uglify js files when system env is production

**Thoughts**: 
a banner image is hard to reponsive, need think deep

**Link(s) to work**: 
1. [SHINO App](https://github.com/kimochg/shino)
2. [SHINO link](https://shino.pervade.tech)
3. [The Tribute Page](http://codepen.io/kimochg/full/OWVKLv/)


**FreeCodeCamp**: 120
___
### Day 7: Januray 10, 2017

**Today's Progress**: 
grok vi, and write down to tinythougts

**Thoughts**: 
The Zen of Vi is great

**Link(s) to work**: 
[Grok Vi](https://github.com/kimochg/TinyThoughts/blob/master/Coding/GrokVi.md)


**FreeCodeCamp**: 120
___
### Day 8: Januray 11, 2017

**Today's Progress**: 
- reading: understanding flexbox
- codepen flexbox portfolio catty music
- register qiniu cloud for image bed

**Thoughts**: 
Learning brand new flexbox model to layout page
[understanding flexbox](https://github.com/kimochg/TinyThoughts/blob/master/Styles/flexbox.md)

**Link(s) to work**: 
[flexbox: catty music](http://codepen.io/kimochg/full/QdyVgV/)

**FreeCodeCamp**: 120
___
### Day 9: Januray 12, 2017

**Today's Progress**: 
- TinyThoughts: understanding flexbox
- codepen flexbox Catty Music

**Thoughts**: 
- flexbox clean css, nested flex layout whole page.
- try add markdown image use local picture, with MWeb

**Link(s) to work**: 
[flexbox: catty music](http://codepen.io/kimochg/full/QdyVgV/)
[understanding flexbox](https://github.com/kimochg/TinyThoughts/blob/master/Styles/flexbox.md)

**FreeCodeCamp**: 120
___
### Day 10: Januray 13, 2017

**Today's Progress**: 
- portfolio with flexbox model and fontawesome

**Thoughts**: 
- pure css is hard to maintain a perfect visual experience
- next, react and material-ui

**Link(s) to work**: 
[Portfolio](http://codepen.io/kimochg/full/dNGmxY/)

**FreeCodeCamp**: 121
___
### Day 11: Januray 14, 2017

**Today's Progress**: 
- Learn ES2015/ES6

**Thoughts**: 
- The ES6 Specialization is pretty cool, build a hard fundation for react

**Link(s) to work**: 
[Learn ES6](https://github.com/kimochg/TinyThoughts/blob/master/Coding/es6.md)

**FreeCodeCamp**: 121
___
### Day 12: Januray 16, 2017

**Today's Progress**: 
- Implement a React Todos App

**Thoughts**: 
- the dispresive state is hard to manage
- the props(methods, data) flow down to child component and forth back.


**Link(s) to work**: 
[React Todos App](https://github.com/kimochg/react-todos)

**FreeCodeCamp**: 156
___
### Day 13: Januray 18, 2017

**Today's Progress**: 
- Redux Todos App

**Thoughts**: 
- single store and pure function
- container component and representational component
- use context(Provider)/connect(mapStateToProps, mapDispatch) to implicitly pass through store


**Link(s) to work**: 
[Redux Todos App](https://github.com/kimochg/redux-todos)

**FreeCodeCamp**: 193
___
### Day 14: Januray 19, 2017

**Today's Progress**: 
- Redux Todos App

**Thoughts**: 
- Container component should rerender itself by subscribe (this.forceUpdate()) when componentWillMount() and unsubscribe when componentWillUnmout()
- Connect() do this implicitly behind the scenario

**Link(s) to work**: 
[Redux Todos App](https://github.com/kimochg/redux-todos)

**FreeCodeCamp**: 193
___
### Day 15: Januray 20, 2017

**Today's Progress**: 
- Redux Todos App

**Thoughts**: 
Redux philosophy
- Try to extract representational component
- Decouple the businees logic in container component from looks
- Use Provider and connect method from react-redux to pass through state, dispatch as props with React context implicitly
- Extract actions to action generator which returns plain object for dispatch

**Link(s) to work**: 
[Redux Todos App](https://github.com/kimochg/redux-todos)

**FreeCodeCamp**: 193
___


