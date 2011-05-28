
# deploy

  Minimalistic shell deployment shell script

## Installation

    $ make install

## Configuration

 By default `deploy(1)` will look for _./deploy.conf_, consisting of one or more environments, `[stage]`, `[production]`, etc, followed by directives.

    [stage]
    key /path/to/some.pem
    user deployer
    host n.n.n.n
    repo git@github.com:visionmedia/express.git
    path /home/ec2-user/deploy-test
    branch origin/master
    post-deploy /home/ec2-user/deploy-test/update

## Directives

### key (optional)

  Path to identity file used by `ssh -i`.
  
      key /path/to/some.pem

### user

   User for deployment.
   
       user deployer

### host

   Server hostname.
   
       host 50.17.255.50

### repo

   GIT repository to clone.
   
       repo git@github.com:visionmedia/express.git

### path

    Deployment path.
    
        path /var/www/myapp.com

### branch

    GIT branch.
    
        branch origin/master

### post-deploy

    Post-deployment command.
    
        post-deploy /var/www/myapp.com/restart

## License 

(The MIT License)

Copyright (c) 2011 TJ Holowaychuk &lt;tj@vision-media.ca&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.