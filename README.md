# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The hosted microservice on AWS can be found here: [http://udagram-odina-image-filter-dev-dev.eu-west-2.elasticbeanstalk.com/](http://udagram-odina-image-filter-dev-dev.eu-west-2.elasticbeanstalk.com/).

To use, append the image url as a query param to the `filteredimage` endpoint of the app url like so: `http://udagram-odina-image-filter-dev-dev.eu-west-2.elasticbeanstalk.com/filteredimage?image_url={IMAGE_URL}`.

To run locally, clone the app and run the command `npm run dev`.

Example use:

http://udagram-odina-image-filter-dev-dev.eu-west-2.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg