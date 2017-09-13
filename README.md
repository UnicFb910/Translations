# Translations

Help translate Netdex into your language.

**It is highly recommended, you do not translate into a language, which you don't speak natively.**

## Why Bother Translating?

For the people that just don't understand English as good as you, it is nice to have human-generated translations - and if you decide to translate a good amount of strings, you will be mentioned in [the Credits](https://netdex.co/credits), which, of course, will require you to specify your Netdex username, first name and, optionally, last name in the Pull Request.

## A Full Guide to Translating using Github

1. First of all, you will need to keep the [two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) of your language in mind.

2. Then, for you to be able to work, you'll need to [Fork this Repository](https://github.com/netdexco/Translations/fork).

3. If you do not spot a `.txt` with your two-letter language code as the name:

    1. In your fork (`github.com/your-username/Translations`), create a new file with `xx.txt` as the name, wherein you replace `xx` with your two-letter language code.
    2. Copy [the contents of the new.txt](https://raw.githubusercontent.com/netdexco/Translations/master/new.txt) into your freshly-created file.

4. Now you can translate from English into your language. Once you have translated enough to end the "translating session," don't forget to commit!

    1. If you are ever unsure what a translation means, feel free to look at the other files, and if they don't help, [Open an Issue](https://github.com/netdexco/Translations/issues/new).

     2. If you can't translate something into a correct sentence, don't hesitate to [Open an Issue](https://github.com/netdexco/Translations/issues/new) and describe the problem as good as possible.

    3. Once you have translated a string (everything after the `=`), you'll have to remove the `# ` in front of the line, to tell Netdex "this is translated."

5. When you feel like your translation is "good enough for now", you may [Create a Pull Request](https://guides.github.com/activities/forking/#making-a-pull-request) for it to be visible on Netdex.
