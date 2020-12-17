# Simple IP Grabber

This is a simple IP grabber using HTML and Pipedream to collect responses,

# Pipedream???

[Pipedream]("https://pipedream.com") is a free to use tool that you can use to collect HTTP requests, like we are doing in this project.

# How to use

### Getting started with Pipedream

Start by making an account on [Pipedream]("https://pipedream.com"), and go to the **Sources** tab
Create a new *"Source"* with the *"App Type"* set to `HTTP` and the *"Source"* to `New Requests`
Give your new *"Source"* a name, and click `Create Source`

Now you should be greeted by a control panel, but most importantly you'll be able to see your *"Endpoint"*.

It should look something like this `https://f598576fdfb78b7f0b205399d9f8a8b7.m.pipedream.net`

Copy the the ID so you only have this `f598576fdfb78b7f0b205399d9f8a8b7`.

Now, think of a redirect URL, for example `https://www.google.com/`, then remove `https://` or `http://` and any `/`,`?`,`#` from the URL so you're left with this `google.com`

### Construct your URL

Take the base URL : `https://fiskdk.github.io/simple-ip-grabber/` and append your endpoint ID after a `#`
Your URL should now look like this : `https://fiskdk.github.io/simple-ip-grabber/#f598576fdfb78b7f0b205399d9f8a8b7`

Now append your redirect URL after a `?`

Like this : `https://fiskdk.github.io/simple-ip-grabber/#f598576fdfb78b7f0b205399d9f8a8b7?google.com`

You can also add a RefID so you it's easier to keep track of your outputs.

To add a RefID, simply append `!` and a custom string of your choice. Example : `!apple`

If you use a ReFID your complete URL should look like this : `https://fiskdk.github.io/simple-ip-grabber/#f598576fdfb78b7f0b205399d9f8a8b7?google.com!apples`

Now what you could do, and properly should do, is use some kind of URL shortener to hide the URL

### ~Jayy <3
