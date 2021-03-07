# 28idea for 28idea.com

28idea founded by 28 participants from Kizuna Group E Project 2013. We tells stories about disaster preparedness and response, volunteer activities, and friendship. 28 comes from the number of our members and IDEA means Information Disaster Education from Indonesia.
This static website created as *memento* of Kizuna Group E Project 2013.

The website can be accessed on [https://28idea.com](https://28idea.com).

It it build based on [Bootstrap](https://getbootstrap.com/).

We collects articles which related to 28idea. Please add the article links on `main`:
```html
<a class="content-links" target="_blank" href="{link of your article}" >
  <div class="col">
    <div class="card shadow-sm bg-light">
      <div class="mx-auto">
        <img class="content-image" src="assets/img/{logo or avatar of author}.png" alt="{description about author}" >
      </div>
      <div class="card-body mx-auto">
        <p class="card-text text-dark">{Author name}</p>
      </div>
    </div>
  </div>
</a>
```

Image on `content-image` is based on `png` file with size 150px x 150px.