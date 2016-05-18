# jenkins-coverage-badge

Added username and password for basic auth.

The MISSING [shields.io](http://shields.io) badge, Jenkins-coverage.

This tiny web server will generate your Jenkins-code-coverage badge!

[![npm](https://img.shields.io/npm/v/jenkins-coverage-badge.svg?style=flat-square)]()

## Install & Run
```bash
# install
$ npm install -g jenkins-coverage-badge

# run with port number (default: 9913)
$ jcb 80
Listening on port 80...

```

Now you can get coverage badge with,

`http://host:port/jenkins/c/http/:jenkins_url/job/:job`

## Example

![coverage](http://d7.mnpk.org/jcb/jenkins/c/http/d7.mnpk.org/jenkins/job/goyo?style=flat-square)
```
![coverage](http://d7.mnpk.org/jcb/jenkins/c/http/d7.mnpk.org/jenkins/job/goyo?style=flat-square)
```
 
## License
MIT
