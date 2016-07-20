# sd-aws-magic-night-jul-2016-ecs

http://ec2contai-ecselast-wrkznymckx4i-509614004.us-west-2.elb.amazonaws.com/magicnight


## Building & pushing new docker images

    $ docker build -t aws-magic-night .
    $ docker tag aws-magic-night:latest 751851535554.dkr.ecr.us-west-2.amazonaws.com/aws-magic-night:latest
    $ docker push 751851535554.dkr.ecr.us-west-2.amazonaws.com/aws-magic-night:latest
