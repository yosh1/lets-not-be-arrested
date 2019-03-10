# lets-not-be-arrested project

[日本語](README.ja.md)

----

`JavaScript` is a dangerous technology that may run malicious programs without user acknowledgement.

As a result, attaching a link to a site that runs an infinite loop of alert like the following with `JavaScript` the other day, a girls junior high school student was questioned and charged by the police. *1

```
■■■■■ (■) {
  ■■■■■ ("■");
}
```


## Best strategy that developers can take to prevent being arrested

### Delete Google Analytics

If you track the user's footprints using Google Analytics you will be arrested, so it is recommended to be deleted.

The corresponding code is here. *1

```
<!-- Global site tag (gtag.js) - Google Analytics -->
<■■■■■■ ■■■■■="" ■■■="■■■■■://■■■.■■■■■■■■■■■■■■■■.■■■/■■■■/■■?■■=■■-■■■■■■■■■-■"></■■■■■■>
<■■■■■■>
    ■■■■■■.■■■■■■■■■ = ■■■■■■.■■■■■■■■■ || [];

    ■■■■■■■■ ■■■■() {
        ■■■■■■■■■.■■■■(■■■■■■■■■);
    }
    ■■■■('■■', ■■■ ■■■■());

    ■■■■('■■■■■■', '■■-■■■■■■■■■-■');
</■■■■■■>
```


### Delete JavaScript from your code.
Let's delete everything from `<script>` to `</script>` .

JavaScript will be prevented from working by deleting these codes.

## Do not expose yourself to JavaScript damage

### Disable JavaScript in your browser

#### Chrome
Open the menu on the top right corner, find `Settings` and open. Enter `javascript` in the search bar. Turn off `javascript` so that Chrome will not allow any sites to run Javascript.

#### Firefox
In the address bar, enter `about:config` .

There will be an alert which shows that the application will be out of warranty.
But remember the risk of being arrested and make sure to agree and turn it off.

Enter `javascript.enabled` in the search bar and double-click to switch to false.

#### Internet Explorer
Select the `Internet options` in the menu.

On the `Security` tab, select `Customize Level`.

Choose `Script` > `Disable` the `Active Script` and restart the browser to make it effect.

## When you have found a new crime
Please fork this project and edit, then send a pull request.

It is not tied to a language, but the language I can surely read is English Japanese only.

## I am looking for people who translate!
Please fork this project and edit, then send a pull request.

## Questions

Q. Why is the code painted black? (*1)

A. Because I might be arrested if you post the code here.
   Thanks to @kazh98 for [pointing out](https://github.com/yoshi1125hisa/lets-not-be-arrested/pull/2)!

Q. I can't find the exact option to change my settings.

A. We know that each browser have large updates every few months. If you find any updates not configured let us know by issues or forking + pull requests.
