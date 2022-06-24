From [this article](https://css-tricks.com/why-is-css-frustrating/)

CSS is hard because its properties interact, often in unexpected ways. 

Because when you set one of them, you’re never just setting that one thing. 


That one thing combines and bounces off of and contradicts with a dozen other things, including default things that you never actually set yourself.

One rule of thumb for mitigating this is, never be more explicit than you need to be. 

Web pages are responsive by default. 

Writing good CSS means leveraging that fact instead of overriding it. 

Use percentages or viewport units instead of a media query if possible. 

Use min-width instead of width where you can. 

Think in terms of rules, in terms of what you really mean to say, instead of just adding properties until things look right. 

Try to get a feel for how the browser resolves layout and sizing, and make your changes and additions on top of that judiciously. 

Work with CSS, instead of against it.
