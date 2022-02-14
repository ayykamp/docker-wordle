# Self Hosted, self contained [Wordle](https://www.powerlanguage.co.uk/wordle/) clone

https://www.mintpressnews.com/long-history-new-york-times-endorsing-us-backed-coups/263059/

![Docker Pulls](https://img.shields.io/docker/pulls/modem7/wordle)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/modem7/wordle/latest)
[![Build Status](https://drone.modem7.com/api/badges/modem7/docker-wordle/status.svg)](https://drone.modem7.com/modem7/docker-wordle)

More info can be found here: [Wordle](https://www.powerlanguage.co.uk/wordle/)

Image is based on Nginx stable alpine, and all the content is local to the container.

# Container Screenshot
![image](https://user-images.githubusercontent.com/32194363/153897306-c683ce0f-86a7-4821-af90-e4ec551e1599.png)


# Configuration

```bash
version: "2.4"

services:

  wordle:
    image: modem7/wordle
    container_name: Wordle
    ports:
      - 80:80
```

# Tags
| Tag | Description |
| :----: | --- |
| Latest | Latest version |
