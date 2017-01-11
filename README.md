#About Security without borders

Security Without Borders is here to help. We can assist with web security assessments, conduct breach investigations and analysis, and generally act as an advisor in questions pertaining to cyber security. As security services are often expensive to come by, SWB offers these services free to organizations and people fighting against human rights abuse, racism, and other injustices. 

## Articles

*[Transmission 1 by the SWB Core team](https://medium.com/security-without-borders/transmission-1-7eaae7bc8caf#.q3p196yjm)

##Contribute

There are several ways to contribute to SWB at this point.
* translate the web-page to different languages
* tell people about the initiative
* join the [Mailing list](https://lists.securitywithoutborders.org/mailman/listinfo/swb-public)

#Deployment

### Setup:
```
$ gem install middleman
$ bundle install
```

**Running on linux?** Install `rb-inotify`. Not needed for OS X though.

```
gem install rb-inotify
```

### Run locally:
```
$ bundle exec middleman server
```

### Build static site:
```
$ bundle exec middleman build
```
