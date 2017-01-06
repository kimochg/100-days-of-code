# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress**: ngResource, Angular Form Validation, user prompting with Bootstrap help-block

**Thoughts**: retreive data from back-end(RESTful API) via ngResource, disable HTML5 form validation, use ng-class/ng-show to promting user.

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 7

### Day 1: January 4, 2017

**Today's Progress**: ngResource $save, CORS

**Thoughts**: send comment with $resource().$save(), support CORS with module(cors), not simple request will have a OPTIONS request as CORS prefilght to get the support server CORS methods, redirect from HTTP to HTTPS when CROS prefilght will cause invalid.

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 32

### Day 2: Januray 5, 2017

**Today's Progress**: Nginx, Express sercurity SSL certificate with Let's encrypt SSL

**Thoughts**: 
HTTPS on whole site, solution 
1. Nginx force HTTPS, backend http visit(backend no need get ssl cert/keys).
2. Nginx force HTTPS, backend https(Nginx proxy to backend https visit, it fails when need CORS but express have redirected http -> https)

[Client] -- HTTP/HTTPS -> [Nginx] <- HTTPS -> [Front-end]
[Front-end] -- HTTPS -> [Nginx] <- HTTPS -> [Back-end]

**Link(s) to work**: 
[MEAN Project - HTTPS on whole site](http://www.jianshu.com/p/3cef55f0ea6f)
[MEAN Project - HTTPS on whole site](https://github.com/kimochg/TinyThoughts/blob/master/Security/MEAN%20project%20-%20HTTPS%20on%20whole%20site.md)

**FreeCodeCamp**: 52

### Day 3: Januray 6, 2017

**Today's Progress**: Sign in support functional implement

**Thoughts**: 
Code can be written in both Facotry and Controller, there is maybe philosophy to do the choice. MVVM

**Link(s) to work**: [SHINO App](https://github.com/kimochg/shino)

**FreeCodeCamp**: 52