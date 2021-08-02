# jenkins-docker

docker-compose up -d

#update .env for admin pass

#03/08 fixed issue with gpg
https://github.com/tianon/gosu/issues/17


#03/08 Slave Build is not working 
Step 7/23 : RUN easy_install jenkins-webapi
 ---> Running in fee98e00a61b
Searching for jenkins-webapi
Reading https://pypi.python.org/simple/jenkins-webapi/
Scanning index of all packages (this may take a while)
Download error on https://pypi.python.org/simple/jenkins-webapi/: [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:590) -- Some packages may not be found!
Couldn't find index page for 'jenkins-webapi' (maybe misspelled?)
Reading https://pypi.python.org/simple/
Download error on https://pypi.python.org/simple/: [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:590) -- Some packages may not be found!
No local packages or download links found for jenkins-webapi
error: Could not find suitable distribution for Requirement.parse('jenkins-webapi')
ERROR: Service 'jenkins-slave' failed to build: The command '/bin/sh -c easy_install jenkins-webapi' returned a non-zero code: 1

