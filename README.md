
[![Deploy]](https://dashboard.heroku.com/new?template=https://github.com/qm6yu77aro/zhen3-KLDR) 

#大海的估量：

========================================================================
addEventListener(
  "fetch", event => {
    let url = new URL(event.request.url);
    url.host = "APPNAME.herokuapp.com";
    let request = new Request(url, event.request);
    event.respondWith(
      fetch(request)
    )
  }
)
========================================================================
