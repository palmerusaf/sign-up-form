# sign-up-form

## Live Preview

[Link](https://palmerusaf.github.io/sign-up-form/)

## purpose

The purpose of this project was to further explore the use of css selectors and how I could make a validation form with custom messages using only html/css.

## How I did it

I used [this](https://css-tricks.com/form-validation-ux-html-css/) guide for a lot of inspiration. It basically makes use of the :placeholder-shown pseudo selector along with a black placeholder to display form invalidation in a less annoying way.
I also reused a trick I learned on my library project involving the ::before pseudo element to display error messages.
To display different messages for each input form i used the attribute selector in css.
I have read using this method is not always accessible but could still be a good fallback in case a validation script fails for some reason.
I tried to produce a custom message if the passwords don't match but it seems this is impossible with only html and css.
For the pattern match on validation I picked up some regex found on [this](https://regexr.com/#native_link#) site.
