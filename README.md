# find_the_site
## Search any website link using any word finds on duckduckgo website, you can bypass blocked ip or others 
filters.
##### Install

```
python -m pip install find_the_site requests bs4 user_agent
```

##### Find the website

```
In [1]: from find_the_site.fw import get_website                                               

In [2]: get_website("UNITED NATIONS")                                                          
Out[2]: 'https://www.un.org/en/'
```
