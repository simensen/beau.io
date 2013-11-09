---
layout: base
---

# TrueNorth PHP Sculpin Uncon Demo

## Source

First, you can see the source for this page [here](https://github.com/simensen/beau.io/blob/master/source/tnphp2013.md).

## Getting Started

To get a jump start on using [Sculpin](https://sculpin.io), download it like this:

    curl -O https://download.sculpin.io/sculpin.phar

You should be able to execute Sculpin by running it like so:

    php sculpin.phar

For these examples, we'll assume that you have done this in some working directory and the clones will be done from this same directory. Use common sense in finding where `sculpin.phar` lives. :)

## Get and Build the TrueNorth PHP Sample Site

    git clone git@github.com:simensen/tnphp2013-sculpin-demo.git
    cd sculpin-blog-skeleton
    php ../sculpin.phar install
    php ../sculpin.phar generate --watch --server

Your newly generated clone of tnphp2013-sculpin-demo is now accessible at http://localhost:8000/.

## Get and Build the Sculpin Blog Skeleton

    git clone git@github.com:sculpin/sculpin-blog-skeleton.git
    cd sculpin-blog-skeleton
    php ../sculpin.phar install
    php ../sculpin.phar generate --watch --server

Your newly generated clone of sculpin-blog-skeleton is now accessible at http://localhost:8000/.
