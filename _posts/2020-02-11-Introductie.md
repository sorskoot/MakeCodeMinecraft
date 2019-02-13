---
layout: post
color: deep-purple
title:  "Introductie"
date:   2019-02-11 10:43:00am
excerpt_separator: <!--more-->
---

# Welcome

Dit is de allereeste post over deze nieuwe site.

<!--more-->

### Code snippet

{% highlight javascript %}
if __name__ =='__main__':
    img_thread = threading.Thread(target=downloadWallpaper)
    img_thread.start()
    st = '\rDownloading Image'
    current = 1
    while img_thread.is_alive():
        sys.stdout.write(st+'.'*((current)%5))
        current=current+1
        time.sleep(0.3)
    img_thread.join()
    print('\nImage of the day downloaded.')
{% endhighlight %}
