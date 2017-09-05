# python-selenium
Use Python Selenium For GUI Automation Test

# How To Start Test
```
# Start container
docker run -d -p 4444:4444 \
    -v /tmp/screenshot:/tmp/screenshot \
    -h selenium --name selenium denny/python-selenium:v1

# Run A Sample Test
docker exec selenium \
   python /home/seluser/selenium_load_page.py \
   --page_url https://www.dennyzhang.com
```