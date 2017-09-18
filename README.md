<a href="https://github.com/DennyZhang?tab=followers"><img align="right" width="200" height="183" src="https://www.dennyzhang.com/wp-content/uploads/denny/watermark/github.png" /></a>

[![Build Status](https://travis-ci.org/DennyZhang/python-selenium.svg?branch=master)](https://travis-ci.org/DennyZhang/python-selenium) [![Docker](https://www.dennyzhang.com/wp-content/uploads/sns/docker.png)](https://hub.docker.com/r/denny/python-selenium/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[![LinkedIn](https://www.dennyzhang.com/wp-content/uploads/sns/linkedin.png)](https://www.linkedin.com/in/dennyzhang001) [![Github](https://www.dennyzhang.com/wp-content/uploads/sns/github.png)](https://github.com/DennyZhang) [![Twitter](https://www.dennyzhang.com/wp-content/uploads/sns/twitter.png)](https://twitter.com/dennyzhang001) [![Slack](https://www.dennyzhang.com/wp-content/uploads/sns/slack.png)](https://www.dennyzhang.com/slack)

- File me [tickets](https://github.com/DennyZhang/python-selenium/issues) or star [the repo](https://github.com/DennyZhang/python-selenium)

# python-selenium
Use Python Selenium For GUI Automation Test

Read more: https://www.dennyzhang.com/python_selenium

# How To Start Test
```
# Start container
docker run -d --restart=always \
    -v /tmp/screenshot:/tmp/screenshot \
    -h selenium --name selenium denny/python-selenium:v1

# Run A Sample Test. 
# With customized test scripts, you can do more!
docker exec selenium \
   python /home/seluser/selenium_load_page.py \
   --page_url https://www.dennyzhang.com --should_save_screenshot

# Check Screenshot
ls -lth /tmp/screenshot
```

# Check more
- TODO

Code is licensed under [MIT License](https://www.dennyzhang.com/wp-content/mit_license.txt).
