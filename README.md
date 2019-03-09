# lets-not-be-arrested project

[日本語](README.ja.md)

----

JavaScript is a dangerous thing to run malicious programs and behave unintentionally by the user.

As a result, by attaching a link to the site which wrote an infinite loop of alert like the following with JavaScript the other day, a girls junior high school student was guided by the police.

```
While (1) {
  alert ("!");
}
```

## Best strategy that developers can take to prevent being arrested

### Delete Google Analytic

If you grasp the user's trends using Google Analytics you will be arrested, so let's delete it.

The corresponding code is here.

```
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXXXXXX-X"></script>
<script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
        dataLayer.push(arguments);
    }
    gtag('js', new Date());

    gtag('config', 'UA-XXXXXXXXX-X');
</script>
```

### Delete JavaScript
Let's delete all from `<script>` to `</script>` .

JavaScript will not work with this!

## Do not make yourself get damaged by JavaScript

### Disable JavaScript in browser

#### Chrome
Open the menu setting and enter javascript in the search bar. Please choose not to allow Javascript to run for all sites from the setting of contents

#### Firefox
In the address bar, enter about: config.

It is out of action! I get a warning, but there is a possibility that I may be arrested. Let's agree.

Enter javascript.enabled in the search bar and double click to switch to false.

#### Internet Explorer
Select the Internet option on the menu.

On the Security tab, select Custom Level.

Choose Script> Disable Active Script and restart the browser, then it will take effect.

When you have found a new crime
Please fork this project and edit, then send a pull request. It is not tied to a language, but the language I can surely read is English Japanese only.

We are looking for people who translate!
Please fork this project and edit, then send a pull request.
